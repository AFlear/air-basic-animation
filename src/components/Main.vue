<template>
  <div>
    <firstScreenManualAnimation ref="first_screen"/>
    <secondScreen  ref="second_screen"/>
  </div>
</template>


<script>
import secondScreen from './secondScreen.vue'
import {serverBus} from "@/main";
import FirstScreenManualAnimation from "@/components/firstScreenManualAnimation";

export default {
  name: 'Main',
  components: {
    FirstScreenManualAnimation,
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
      if (!isSecond) {
        window.scrollTo(x, y);
        this.secondScreen = true;
      } else {
        window.scrollTo(0, 0);
        this.secondScreen = false;
      }
    },

  },
  created() {
    serverBus.$on('finished', () => {
      const el = document.getElementById('second_screen').getBoundingClientRect();
      this.scrollTo(el.top + window.scrollX, el.top + window.scrollY, false);
      setTimeout(()=>{
        document.getElementById('forScroll').style.height = '1000px'

      }, 1000)
    });
  }

}
</script>