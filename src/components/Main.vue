<template>
  <div>
    <!--  All animation triggered by 1 scroll  -->
    <!--    <firstScreen ref="first_screen"/>-->
    <!--    All animation are triggered by separate scrolls -->
    <!--    <firstScreenManualAnimation ref="first_screen"/>-->
    <!--    All Animation are automatic-->
    <firstScreenAutomatic ref="first_screen"/>
    <secondScreen ref="second_screen"/>
  </div>
</template>


<script>
// import firstScreen from './firstScreen.vue'
import secondScreen from './secondScreen.vue'
import firstScreenAutomatic from './firstScreenAutomatic'
// import {serverBus} from "@/main";
// import FirstScreenManualAnimation from "@/components/firstScreenManualAnimation";

export default {
  name: 'Main',
  components: {
    // FirstScreenManualAnimation,
    firstScreenAutomatic,
    // firstScreen,
    secondScreen
  },
  data() {
    return {
      isFinished: false,
      isSecondScreen: false,
    }
  },
  methods: {
    scrollTo(x, y, isSecond) {
      window.document.removeEventListener("wheel", this.scrollToSecondScreen);
      if (!isSecond) {
        window.scrollTo(x, y);
        this.secondScreen = true;
        window.document.addEventListener("wheel", () => this.scrollToSecondScreen, {passive: false});
      } else {
        window.scrollTo(0, 0);
        this.secondScreen = false;
        window.document.addEventListener("wheel", () => this.scrollToSecondScreen, {passive: false});
      }
    },
    // Version for firstScreenManualAnimation
    // scrollToSecondScreen() {
    //   if (this.isFinished && !this.isSecondScreen) {
    //     const el = document.getElementById('second_screen').getBoundingClientRect();
    //     this.scrollTo(el.top + window.scrollX, el.top + window.scrollY, false);
    //   }
    //   if (this.isSecondScreen) {
    //     this.isSecondScreen = false;
    //     this.scrollTo(0, 0, true);
    //   }
    // }

    // Version for firstScreen
    // scrollToSecondScreen() {
    //   const el = document.getElementById('second_screen')
    //   if (el) {
    //     el.scrollIntoView({behavior: 'smooth'})
    //     this.isFinished = false;
    //   }
    // },
    //Version for firstScreenAutomatic
    scrollToSecondScreen() {
        const el = document.getElementById('second_screen')
        if (el) {
          el.scrollIntoView({behavior: 'smooth'})
          this.isFinished = false;
        }
    },

  },
  created() {
    // Version for firstScreen and firstScreenManualAnimation
    // serverBus.$on('finished', () => {
    //   this.isFinished = true;
    //   setTimeout(() => {
    //     this.scrollToSecondScreen();
    //   }, 10000)
    // });
    //Version for firstScreenAutomatic
    setTimeout(() => {
      this.scrollToSecondScreen();
    }, 13000)
  }

}
</script>