<template>
  <div class="forScroll">
    <div class="header fixed-top">
      <div class="section section--header">
        <div class="container">
          <div class="row">
            <div class="col-lg-8">
              <div class="d-flex align-items-center">
                <a href="https://air.io/en" title="air.io" class="header__logo link link--white">air.io</a>
                <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse"
                        aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>

                <ul class="d-flex justify-content-between align-items-center m-0 p-0">
                  <li class="header__item">
                    <a class="link link--white" title="creators ecosystem" href="#">creators ecosystem</a>
                  </li>
                  <li class="header__item">
                    <a class="link link--white" title="brands" href="#">brands</a>
                  </li>
                  <li class="header__item">
                    <a class="link link--white" href="#" title="career">career</a>
                  </li>
                  <li class="header__item">
                    <a class="link link--white" title="blog" href="#">blog</a>
                  </li>
                  <li class="header__item">
                    <a class="link link--white" title="f.a.q." href="#">f.a.q.</a>
                  </li>
                </ul>
              </div>

            </div>
            <div class="col-lg-4 d-flex align-items-center position-relative">
              <button type="button" class="button button--sm button--gradient button--radius-6 me-0">
                <svg width="16" height="18" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                      d="M1.093 5.386l6.699 4.263a.6108.6108 0 00.6541 0l6.699-4.263a.6102.6102 0 00.282-.514.6084.6084 0 00-.282-.5134L8.4461.095a.6104.6104 0 00-.654 0L1.093 4.3586a.6084.6084 0 00-.282.5134.61.61 0 00.282.514z"
                      fill="#fff"/>
                  <path
                      d="M15.1449 9.2301l-1.886-1.2003-4.1588 2.6467a1.8302 1.8302 0 01-.9811.2856 1.824 1.824 0 01-.9793-.285L2.979 8.0298 1.093 9.23a.6101.6101 0 00-.282.514c0 .2083.1066.402.282.5134l6.699 4.2636a.6103.6103 0 00.654 0l6.6989-4.2636a.6083.6083 0 00.282-.5134.6102.6102 0 00-.282-.514z"
                      fill="#fff"/>
                </svg>
              </button>
              <div class="section--bg-gradient"></div>
            </div>
          </div>
        </div>
      </div>

      <div class="container" ref="header__animate">
        <div class="section--underline pt-3">
          <div class="d-flex justify-content-between">
            <a href="#" title="basic">
              <svg width="132" height="41" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g filter="url(#filter0_d)">
                  <path
                      d="M32.1819 18.4331c3.0116 1.7186 4.5245 4.3251 4.5387 7.8195.0119 2.9065-1.0071 5.2947-3.057 7.1646-2.0498 1.8699-4.577 2.8109-7.5815 2.8232l-14.5491.0592-.1397-34.2906 13.5203-.055c2.9392-.012 5.4086.8923 7.4082 2.713 2.0321 1.788 3.0539 4.0862 3.0653 6.8948.0116 2.8412-1.0568 5.1316-3.2052 6.8713zm-7.2425-10.16l-6.7602.0276.0308 7.544 6.7601-.0276c1.0451-.0042 1.909-.367 2.5919-1.0883.7156-.7214 1.0711-1.6209 1.0667-2.6986-.0043-1.0777-.3509-1.9744-1.0396-2.69-.6888-.7158-1.572-1.0714-2.6497-1.067zm1.1169 21.648c1.143-.0047 2.0886-.3841 2.8367-1.1383.7479-.7868 1.1195-1.7681 1.1147-2.9438-.0047-1.143-.3841-2.0885-1.1383-2.8366-.7543-.7807-1.703-1.1688-2.846-1.1641l-7.7889.0317.0329 8.0828 7.7889-.0317zm33.7405-18.3118l6.3193-.0258.0998 24.4934-6.3193.0257-.0118-2.8902c-1.8844 2.3917-4.5412 3.5946-7.9702 3.6085-3.2658.0133-6.0794-1.2162-8.4409-3.6886-2.3289-2.5052-3.5008-5.5703-3.5156-9.1953-.0147-3.625 1.1322-6.6833 3.4408-9.1747 2.3411-2.5242 5.1445-3.793 8.4103-3.8063 3.4291-.014 6.0955 1.1672 7.9994 3.5435l-.0118-2.8902zM48.2083 28.9001c1.2788 1.2684 2.898 1.8987 4.8574 1.8907 1.9595-.008 3.5734-.6514 4.8419-1.9302 1.301-1.3117 1.9474-2.9799 1.9391-5.0047-.0082-2.0247-.6681-3.6713-1.9796-4.9396-1.279-1.3011-2.8982-1.9477-4.8577-1.9397-1.9594.008-3.5733.6677-4.8417 1.9792-1.2684 1.2788-1.8985 2.9306-1.8903 4.9554.0083 2.0248.6519 3.6878 1.9309 4.9889zm29.3045-10.4068c.0026.6532.4294 1.1903 1.2802 1.6114.8834.3883 1.9462.7432 3.1885 1.0647 1.2422.2889 2.4848.6757 3.7278 1.1605 1.2429.4522 2.2911 1.2317 3.1447 2.3386.8863 1.1068 1.3329 2.493 1.3396 4.1585.0103 2.5146-.9289 4.4616-2.8174 5.841-1.8561 1.3465-4.1884 2.0255-6.9969 2.037-5.0293.0205-8.4663-1.9087-10.311-5.7875l5.4739-3.1085c.7272 2.1198 2.3317 3.1747 4.8137 3.1645 2.2534-.0091 3.3772-.7159 3.3715-2.1202-.0027-.6531-.4457-1.1738-1.329-1.5621-.8509-.4211-1.8974-.7924-3.1398-1.114-1.2423-.3215-2.4849-.7246-3.7279-1.2095-1.243-.4848-2.3075-1.2479-3.1935-2.2894-.8535-1.0742-1.2835-2.4114-1.2901-4.0117-.0098-2.4166.8642-4.3144 2.6222-5.6932 1.7904-1.4116 4.0083-2.1228 6.6536-2.1336 1.9921-.0081 3.8065.4417 5.4431 1.3495 1.6365.8751 2.9316 2.1435 3.8855 3.8052l-5.3766 2.9612c-.7905-1.6624-2.1002-2.4898-3.9291-2.4824-.8164.0033-1.5015.1857-2.0552.5472-.5211.3614-.7803.8523-.7778 1.4728zm19.7973-9.976c-1.045.0042-1.961-.3677-2.7478-1.1156-.7543-.7807-1.1336-1.6936-1.1379-2.7387-.0042-1.045.3676-1.961 1.1155-2.7478.7806-.787 1.6935-1.1826 2.7385-1.1869 1.0777-.0044 1.9937.3838 2.7476 1.1645.787.7806 1.183 1.6935 1.187 2.7385.005 1.045-.384 1.961-1.164 2.748-.7483.7542-1.6612 1.1335-2.7389 1.138zm-3.0233 27.4452l-.0998-24.4933 6.319-.0258.1 24.4933-6.3192.0258zm23.7652.589c-3.691.015-6.782-1.2134-9.274-3.6853-2.46-2.472-3.697-5.5368-3.712-9.1945-.015-3.6577 1.198-6.7325 3.637-9.2244 2.472-2.4921 5.553-3.7457 9.243-3.7607 2.384-.0098 4.558.5529 6.522 1.6879 1.964 1.1351 3.457 2.6639 4.477 4.5866l-5.425 3.2063c-.494-1.0104-1.248-1.8074-2.263-2.3911-.982-.5839-2.094-.8733-3.335-.8682-1.894.0077-3.459.6509-4.694 1.9296-1.236 1.2461-1.85 2.8488-1.842 4.8083.007 1.9268.634 3.5245 1.881 4.7931 1.246 1.2359 2.816 1.85 4.71 1.8423 1.274-.0052 2.399-.2874 3.377-.8465 1.01-.592 1.758-1.3952 2.243-2.4096l5.5 3.1128c-1.07 1.9312-2.583 3.4887-4.537 4.6723-1.955 1.151-4.124 1.7314-6.508 1.7411z"
                      fill="#32353D"/>
                  <path
                      d="M32.1819 18.4331c3.0116 1.7186 4.5245 4.3251 4.5387 7.8195.0119 2.9065-1.0071 5.2947-3.057 7.1646-2.0498 1.8699-4.577 2.8109-7.5815 2.8232l-14.5491.0592-.1397-34.2906 13.5203-.055c2.9392-.012 5.4086.8923 7.4082 2.713 2.0321 1.788 3.0539 4.0862 3.0653 6.8948.0116 2.8412-1.0568 5.1316-3.2052 6.8713zm-7.2425-10.16l-6.7602.0276.0308 7.544 6.7601-.0276c1.0451-.0042 1.909-.367 2.5919-1.0883.7156-.7214 1.0711-1.6209 1.0667-2.6986-.0043-1.0777-.3509-1.9744-1.0396-2.69-.6888-.7158-1.572-1.0714-2.6497-1.067zm1.1169 21.648c1.143-.0047 2.0886-.3841 2.8367-1.1383.7479-.7868 1.1195-1.7681 1.1147-2.9438-.0047-1.143-.3841-2.0885-1.1383-2.8366-.7543-.7807-1.703-1.1688-2.846-1.1641l-7.7889.0317.0329 8.0828 7.7889-.0317zm33.7405-18.3118l6.3193-.0258.0998 24.4934-6.3193.0257-.0118-2.8902c-1.8844 2.3917-4.5412 3.5946-7.9702 3.6085-3.2658.0133-6.0794-1.2162-8.4409-3.6886-2.3289-2.5052-3.5008-5.5703-3.5156-9.1953-.0147-3.625 1.1322-6.6833 3.4408-9.1747 2.3411-2.5242 5.1445-3.793 8.4103-3.8063 3.4291-.014 6.0955 1.1672 7.9994 3.5435l-.0118-2.8902zM48.2083 28.9001c1.2788 1.2684 2.898 1.8987 4.8574 1.8907 1.9595-.008 3.5734-.6514 4.8419-1.9302 1.301-1.3117 1.9474-2.9799 1.9391-5.0047-.0082-2.0247-.6681-3.6713-1.9796-4.9396-1.279-1.3011-2.8982-1.9477-4.8577-1.9397-1.9594.008-3.5733.6677-4.8417 1.9792-1.2684 1.2788-1.8985 2.9306-1.8903 4.9554.0083 2.0248.6519 3.6878 1.9309 4.9889zm29.3045-10.4068c.0026.6532.4294 1.1903 1.2802 1.6114.8834.3883 1.9462.7432 3.1885 1.0647 1.2422.2889 2.4848.6757 3.7278 1.1605 1.2429.4522 2.2911 1.2317 3.1447 2.3386.8863 1.1068 1.3329 2.493 1.3396 4.1585.0103 2.5146-.9289 4.4616-2.8174 5.841-1.8561 1.3465-4.1884 2.0255-6.9969 2.037-5.0293.0205-8.4663-1.9087-10.311-5.7875l5.4739-3.1085c.7272 2.1198 2.3317 3.1747 4.8137 3.1645 2.2534-.0091 3.3772-.7159 3.3715-2.1202-.0027-.6531-.4457-1.1738-1.329-1.5621-.8509-.4211-1.8974-.7924-3.1398-1.114-1.2423-.3215-2.4849-.7246-3.7279-1.2095-1.243-.4848-2.3075-1.2479-3.1935-2.2894-.8535-1.0742-1.2835-2.4114-1.2901-4.0117-.0098-2.4166.8642-4.3144 2.6222-5.6932 1.7904-1.4116 4.0083-2.1228 6.6536-2.1336 1.9921-.0081 3.8065.4417 5.4431 1.3495 1.6365.8751 2.9316 2.1435 3.8855 3.8052l-5.3766 2.9612c-.7905-1.6624-2.1002-2.4898-3.9291-2.4824-.8164.0033-1.5015.1857-2.0552.5472-.5211.3614-.7803.8523-.7778 1.4728zm19.7973-9.976c-1.045.0042-1.961-.3677-2.7478-1.1156-.7543-.7807-1.1336-1.6936-1.1379-2.7387-.0042-1.045.3676-1.961 1.1155-2.7478.7806-.787 1.6935-1.1826 2.7385-1.1869 1.0777-.0044 1.9937.3838 2.7476 1.1645.787.7806 1.183 1.6935 1.187 2.7385.005 1.045-.384 1.961-1.164 2.748-.7483.7542-1.6612 1.1335-2.7389 1.138zm-3.0233 27.4452l-.0998-24.4933 6.319-.0258.1 24.4933-6.3192.0258zm23.7652.589c-3.691.015-6.782-1.2134-9.274-3.6853-2.46-2.472-3.697-5.5368-3.712-9.1945-.015-3.6577 1.198-6.7325 3.637-9.2244 2.472-2.4921 5.553-3.7457 9.243-3.7607 2.384-.0098 4.558.5529 6.522 1.6879 1.964 1.1351 3.457 2.6639 4.477 4.5866l-5.425 3.2063c-.494-1.0104-1.248-1.8074-2.263-2.3911-.982-.5839-2.094-.8733-3.335-.8682-1.894.0077-3.459.6509-4.694 1.9296-1.236 1.2461-1.85 2.8488-1.842 4.8083.007 1.9268.634 3.5245 1.881 4.7931 1.246 1.2359 2.816 1.85 4.71 1.8423 1.274-.0052 2.399-.2874 3.377-.8465 1.01-.592 1.758-1.3952 2.243-2.4096l5.5 3.1128c-1.07 1.9312-2.583 3.4887-4.537 4.6723-1.955 1.151-4.124 1.7314-6.508 1.7411z"
                      fill="url(#paint0_linear)" fill-opacity=".13"/>
                </g>
                <path
                    d="M.6853 33.0639c0-.5112.1721-.9414.5163-1.2907.3442-.3492.7668-.5239 1.268-.5239.501 0 .9237.1747 1.2679.5239.3441.3493.5162.7795.5162 1.2907v.9339H6v1.0478H.6853v-1.9817zm2.589 0c0-.2227-.0759-.4074-.2278-.5542-.1569-.1468-.3492-.2202-.577-.2202-.2328 0-.4251.0734-.577.2202-.1519.1468-.2278.3315-.2278.5542v.9339h1.6096v-.9339zM6 27.6919l-.9566.3189v2.1182L6 30.4479v1.1313L.6853 29.7191v-1.2983L6 26.553v1.1389zM4.064 29.795v-1.4578l-2.1715.7289 2.1714.7289zm2.0423-6.0859c0 .7997-.2657 1.4602-.7972 1.9816-.5315.5213-1.187.782-1.9665.782-.7845 0-1.44-.2607-1.9664-.782-.5315-.5214-.7972-1.1819-.7972-1.9816 0-.4809.1139-.9238.3417-1.3287.2227-.41.5264-.7289.911-.9567l.524.9035c-.238.1316-.4227.3189-.5543.5619-.1367.2429-.205.5163-.205.82 0 .5162.162.9338.486 1.2527.3239.3138.744.4707 1.2603.4707.5112 0 .9288-.1569 1.2527-.4707.324-.3189.486-.7365.486-1.2527 0-.3037-.0659-.5771-.1975-.82-.1366-.248-.3214-.4353-.5542-.5619l.5238-.9035c.3847.2278.691.5442.9187.9491.2227.4049.334.8503.334 1.3363zM6 16.627v1.2072l-2.4903 1.8981H6v1.0478H.6853v-1.0477h2.346l-2.346-1.8222V16.703l2.5814 1.9664L6 16.627zm0-4.0681l-.9566.3189v2.1183L6 15.315v1.1313L.6853 14.5861v-1.2983L6 11.4201v1.1388zM4.064 14.662v-1.4577l-2.1715.7289 2.1714.7288zm-.9188-8.7812h.41c.7593 0 1.3743.243 1.845.7289.4707.4859.706 1.1135.706 1.8829 0 .82-.2656 1.5008-.7971 2.0424-.5365.5365-1.1895.8048-1.9589.8048-.7744 0-1.4299-.2658-1.9664-.7972C.8473 10.006.579 9.3429.579 8.5533c0-.496.1139-.949.3417-1.359.2227-.41.5213-.7289.8959-.9566l.5163.8958c-.2177.1266-.3948.319-.5315.577-.1367.2532-.205.5366-.205.8504 0 .5062.167.9238.501 1.2528.3291.3239.7467.4859 1.2528.4859.5011 0 .9162-.1645 1.2452-.4935.324-.334.486-.7744.486-1.321 0-.405-.0887-.739-.2658-1.0023-.1822-.2683-.4303-.4505-.744-.5467v1.6097h-.9264v-2.665zm1.8526-1.793V1.848H6v3.2876H.6853V1.886h1.0022v2.2018h1.1313v-2.012h.987v2.012h1.192z"
                    fill="#39323E"/>
                <defs>
                  <linearGradient id="paint0_linear" x1="69.3948" y1="-9.9365" x2="69.6387" y2="49.9361"
                                  gradientUnits="userSpaceOnUse">
                    <stop stop-color="red"/>
                    <stop offset="1" stop-color="#3E008C" stop-opacity="0"/>
                  </linearGradient>
                  <filter id="filter0_d" x="9.0998" y=".0405" width="122.29" height="40.6798"
                          filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
                    <feFlood flood-opacity="0" result="BackgroundImageFix"/>
                    <feColorMatrix in="SourceAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/>
                    <feOffset dy="1.6055"/>
                    <feGaussianBlur stdDeviation="1.1468"/>
                    <feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.05 0"/>
                    <feBlend in2="BackgroundImageFix" result="effect1_dropShadow"/>
                    <feBlend in="SourceGraphic" in2="effect1_dropShadow" result="shape"/>
                  </filter>
                </defs>
              </svg>
            </a>
            <div class="menu--inner">
              <a class="menu--inner__item" title="About basic" aria-current="page" href="#">
                About basic
              </a>
              <a class="menu--inner__item" title="Creators Ecosystem" href="#">Creators Ecosystem</a>

              <a class="menu--inner__item" href="#" title="What's inside">
                What's inside
                <span class="badge text-white align-text-bottom">16</span>
              </a>
              <div class="ms-4">
                <a href="#" class="button button-md button--border button--radius-6 text-uppercase" title="Get Basic">
                  Get Basic
                </a>
              </div>
            </div>
          </div>

        </div>
      </div>

    </div>

    <section class="section section--basic fixed" id="first_screen">
      <div class="container position-relative">
        <div class="row">
          <div class="col-xs-12">
            <div class="icon--content">
              <div class="icon icon--right-1  icons-right   ">
                <img :src="ToolBox" alt="Product">
              </div>
              <div class="icon icon--right-2  icons-right  ">
                <img :src="Referral" alt="Product">
              </div>
              <div class="icon icon--right-3  icons-right   ">
                <img :src="Finances" alt="Product">
              </div>
              <div class="icon icon--right-4  icons-right   ">
                <img :src="Hack" alt="Product">
              </div>
              <div class="icon icon--right-5  icons-right  ">
                <img :src="Copyright" alt="Product">
              </div>
              <div class="icon icon--right-6  icons-right  ">
                <img :src="Instagram" alt="Product">
              </div>
              <div class="icon icon--left-1  icons-left  ">
                <img :src="Messenger" alt="Product">
              </div>
              <div class="icon  icon--left-2  icons-left  ">
                <img :src="Design" alt="Product">
              </div>
              <div class="icon icon--left-3  icons-left  ">
                <img :src="Payments" alt="Product">
              </div>
              <div class="icon icon--left-4  icons-left  ">
                <img :src="Music" alt="Product">
              </div>
              <div class="icon icon--left-5  icons-left  ">
                <img :src="Meetups" alt="Product">
              </div>
              <div class="icon icon--left-6  icons-left  "
                   data-wow-delay="0.1s">
                <img :src="Moderation" alt="Product"></div>
            </div>

            <div class="basic">
              <div class="basic__head" ref="body">

                <div class="basic__title ">
                  <div class="basic__text--left">
                    Package
                  </div>
                  <div class="basic__text--center">
                    Basic
                  </div>
                </div>

              </div>
              <div class="basic__body">
                <div class="basic__text basic__body__strings body__text-1">
                  16 essential services to support, develop and
                </div>
                <div class="basic__text basic__body__strings  body__text-2">
                  protect your creativity on YouTube and beyond
                </div>
                <div class="basic__text--sub body__text-3 mt-3">
                  Accessible immediately after connecting to AIR Creators Ecosystem.
                </div>
                <div class="basic__button pt-4  basic__button mt-4">
                  <a href="#" class="basic-button mx-auto basic-button-big basic-button-blue">
                    Get now </a>
                </div>
              </div>
              <div class="element element--right svg__circle">
                <svg width="163" height="155" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                      d="M23.4411 95.6576c-.285 16.9424 26.4517 51.2134 72.9123 39.1074C136.604 124.278 150.245 95.5986 148.9 68.8601c-1.345-26.7385-38.251-56.0048-73.6909-52.0807-35.9533 3.9809-70.464 40.6827-60.0907 87.7096"
                      stroke="#B0B0B0" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <div class="element__body">
                  <div class="element__number  right__first__animation">100%
                  </div>
                  <div class="element__text  right__second__animation ">
                    Must Have for
                  </div>
                  <div class="element__text  right__second__animation ">
                    YouTubers
                  </div>
                </div>
              </div>
              <div class="element element--left left__arrow__animation">
                <svg width="46" height="35" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                      d="M1.836 33.5145C8.7772 22.1234 29.6498 6.9141 44.3028 2.9071m0 0l-7.0279-1.194m7.0279 1.194l-3.7908 4.3063"
                      stroke="#B0B0B0" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <div class="element__body">
                  <div class="element__text   left__first__animation">
                    Not
                    provided by
                  </div>
                  <div class="element__text  left__first__animation ">
                    AdSense
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="scrollElement"></div>

  </div>
</template>

<script>
import gsap from 'gsap';
import {ScrollTrigger} from 'gsap/ScrollTrigger';
import {serverBus} from "@/main";

gsap.registerPlugin(ScrollTrigger);

export default {
  name: 'firstScreenManualAnimation',
  data() {
    return {
      ToolBox: require('@/assets/svg/toolbox.svg'),
      Referral: require('@/assets/svg/referral.svg'),
      Finances: require('@/assets/svg/finances.svg'),
      Hack: require('@/assets/svg/hack.svg'),
      Copyright: require('@/assets/svg/copyright.svg'),
      Instagram: require('@/assets/svg/instagram.svg'),
      Messenger: require('@/assets/svg/messenger.svg'),
      Design: require('@/assets/svg/design.svg'),
      Payments: require('@/assets/svg/payments.svg'),
      Music: require('@/assets/svg/music.svg'),
      Meetups: require('@/assets/svg/meetups.svg'),
      Moderation: require('@/assets/svg/moderation.svg'),
    }
  },
  methods: {},
  mounted() {
    gsap.registerPlugin(ScrollTrigger);
    const firstTime = gsap.timeline();
    ScrollTrigger.create({
      animation: firstTime,
      start: "1% 1%",
      end: '2% 2%',
      scrub: 2,
    });

    firstTime.fromTo(this.$refs.header__animate, {
      autoAlpha: 0,
      y: -80,
    }, {
      autoAlpha: 1,
      y: 0,
      duration: 2
    }, 0)

    const body = gsap.timeline();
    ScrollTrigger.create({
      animation: body,
      start: "3%",
      end: '9%',
      scrub: 4,
    });
    body.fromTo(this.$refs.body, {
      autoAlpha: 0,
      y: 10,
      duration: 3
    }, {
      autoAlpha: 1,
      y: -50,
      duration: 3
    }, 1)

    const lowerT = gsap.timeline();
    const lower = document.querySelectorAll('.body__text-1');
    ScrollTrigger.create({
      animation: lowerT,
      start: "10% 10%",
      end: '13% 13%',
      scrub: 2.
    });
    lower.forEach((e) => {
      lowerT.fromTo(e, {
        autoAlpha: 0,
        y: 0,
      }, {
        autoAlpha: 1,
        y: -20,
        duration: 3
      }, 2)
    });

    const lowerT2 = gsap.timeline();
    const lower2 = document.querySelectorAll('.body__text-2');
    ScrollTrigger.create({
      animation: lowerT2,
      start: "11% 11%",
      end: '14% 14%',
      scrub: 2,
    });
    lower2.forEach((e) => {
      lowerT2.fromTo(e, {
        autoAlpha: 0,
        y: 0,
        duration: 2
      }, {
        autoAlpha: 1,
        y: -20,
        duration: 3
      }, 2)
    });

    const lower__secondT = gsap.timeline();
    const lower__second = document.querySelectorAll('.body__text-3');
    ScrollTrigger.create({
      animation: lower__secondT,
      start: "14%",
      end: '17%',
      scrub: 3,
    });
    lower__second.forEach((e) => {
      lower__secondT.fromTo(e, {
        autoAlpha: 0,
        y: 0,
        duration: 3
      }, {
        autoAlpha: 1,
        y: -30,
        duration: 3
      }, 2)
    });

    const animateButton = gsap.timeline();
    const aButton = document.querySelectorAll('.basic__button');
    ScrollTrigger.create({
      animation: animateButton,
      start: "18%",
      end: '23%',
      scrub: 3,
    });
    aButton.forEach((e) => {
      animateButton.fromTo(e, {
        autoAlpha: 0,
        y: 0,
        duration: 3
      }, {
        autoAlpha: 1,
        y: -40,
        duration: 3
      }, 3)
    });


    const right__first__animationT = gsap.timeline();
    const right__first__animation = document.querySelectorAll('.right__first__animation');
    ScrollTrigger.create({
      animation: right__first__animationT,
      start: "24%",
      end: '26%',
      scrub: 2,
    });
    right__first__animation.forEach((e) => {
      right__first__animationT.fromTo(e, {
        autoAlpha: 0,
        x: -30,
        duration: 2,
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,
      }, 4)
    });


    const right__second__animationT = gsap.timeline();
    const right__second__animation = document.querySelectorAll('.right__second__animation');
    ScrollTrigger.create({
      animation: right__second__animationT,
      start: "24%",
      end: '26%',
      scrub: 2
    });
    right__second__animation.forEach((e) => {
      right__second__animationT.fromTo(e, {
        autoAlpha: 0,
        y: 20,
        duration: 0.5,
      }, {
        autoAlpha: 1,
        y: -5,
        duration: 1,
        onStart: () => {
          document.getElementsByClassName('svg__circle')[0].classList.add('animate_svg')
        }
      }, 4)
    });



    const left__first__animationT = gsap.timeline();
    const left__first__animation = document.querySelectorAll('.left__first__animation');
    ScrollTrigger.create({
      animation: left__first__animationT,
      start: "27%",
      end: '30%',
      scrub: 3,
    });
    left__first__animation.forEach((e) => {
      left__first__animationT.fromTo(e, {
        autoAlpha: 0,
        y: 20,
      }, {
        autoAlpha: 1,
        y: 0,
        duration: 2,
        onStart: () => {
          document.getElementsByClassName('left__arrow__animation')[0].classList.add('animate_svg')
        }
      }, 5);
    });


    const iconsLeftT = gsap.timeline();
    const iconsLeft = document.querySelectorAll('.icon--left-1');
    ScrollTrigger.create({
      animation: iconsLeftT,
      start: "31%",
      end: '40%',
      scrub: 1,
    });
    iconsLeft.forEach((e) => {
      iconsLeftT.fromTo(e, {
        autoAlpha: 0,
        x: -50,
        duration: 3
      }, {
        autoAlpha: 1,
        x: 10,
        duration: 3,
      }, 6)
    });

    const iconsLeftT2 = gsap.timeline();
    const iconsLeft2 = document.querySelectorAll('.icon--left-2');
    ScrollTrigger.create({
      animation: iconsLeftT2,
      start: "31%",
      end: '40%',
      scrub: 2,
    });
    iconsLeft2.forEach((e) => {
      iconsLeftT2.fromTo(e, {
        autoAlpha: 0,
        x: -60,
        duration: 2
      }, {
        autoAlpha: 1,
        x: 20,
        duration: 2,
      }, 6)
    });


    const iconsLeftT3 = gsap.timeline();
    const iconsLeft3 = document.querySelectorAll('.icon--left-3');
    ScrollTrigger.create({
      animation: iconsLeftT3,
      start: "31%",
      end: '40%',
      scrub: 3,
    });
    iconsLeft3.forEach((e) => {
      iconsLeftT3.fromTo(e, {
        autoAlpha: 0,
        x: -70,
        duration: 3
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 3,
      }, 6)
    });

    const iconsLeftT4 = gsap.timeline();
    const iconsLeft4 = document.querySelectorAll('.icon--left-4');
    ScrollTrigger.create({
      animation: iconsLeftT4,
      start: "31%",
      end: '40%',
      scrub: 3,
    });
    iconsLeft4.forEach((e) => {
      iconsLeftT4.fromTo(e, {
        autoAlpha: 0,
        x: -60,
        duration: 2
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,
      }, 6)
    });


    const iconsLeftT5 = gsap.timeline();
    const iconsLeft5 = document.querySelectorAll('.icon--left-5');
    ScrollTrigger.create({
      animation: iconsLeftT5,
      start: "31%",
      end: '40%',
      scrub: 2,
    });
    iconsLeft5.forEach((e) => {
      iconsLeftT5.fromTo(e, {
        autoAlpha: 0,
        x: -70,
        duration: 3
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 3,
      }, 6)
    });

    const iconsLeftT6 = gsap.timeline();
    const iconsLeft6 = document.querySelectorAll('.icon--left-6');
    ScrollTrigger.create({
      animation: iconsLeftT6,
      start: "31%",
      end: '40%',
      scrub: 3,
    });
    iconsLeft6.forEach((e) => {
      iconsLeftT6.fromTo(e, {
        autoAlpha: 0,
        x: -80,
        duration: 2
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,
      }, 6)
    });

    const iconsRightT = gsap.timeline();
    const iconsRight = document.querySelectorAll('.icon--right-1');
    ScrollTrigger.create({
      animation: iconsRightT,
      start: "31%",
      end: '40%',
      scrub: 1,
    });
    iconsRight.forEach((e) => {
      iconsRightT.fromTo(e, {
        autoAlpha: 0,
        x: 50,
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,
      }, 6)
    });

    const iconsRightT2 = gsap.timeline();
    const iconsRight2 = document.querySelectorAll('.icon--right-2');
    ScrollTrigger.create({
      animation: iconsRightT2,
      start: "31%",
      end: '40%',
      scrub: 2,
    });
    iconsRight2.forEach((e) => {
      iconsRightT.fromTo(e, {
        autoAlpha: 0,
        x: 60,
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2
      }, 6)
    });

    const iconsRightT3 = gsap.timeline();
    const iconsRight3 = document.querySelectorAll('.icon--right-3');
    ScrollTrigger.create({
      animation: iconsRightT3,
      start: "31%",
      end: '40%',
      scrub: 2,
    });
    iconsRight3.forEach((e) => {
      iconsRightT.fromTo(e, {
        autoAlpha: 0,
        x: 40,
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,
      }, 6)
    });

    const iconsRightT4 = gsap.timeline();
    const iconsRight4 = document.querySelectorAll('.icon--right-4');
    ScrollTrigger.create({
      animation: iconsRightT4,
      start: "31%",
      end: '40%',
      scrub: 3
    });
    iconsRight4.forEach((e) => {
      iconsRightT4.fromTo(e, {
        autoAlpha: 0,
        x: 70,
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,
      }, 6)
    });

    const iconsRightT5 = gsap.timeline();
    const iconsRight5 = document.querySelectorAll('.icon--right-5');
    ScrollTrigger.create({
      animation: iconsRightT5,
      start: "31%",
      end: '40%',
      scrub: 2
    });
    iconsRight5.forEach((e) => {
      iconsRightT5.fromTo(e, {
        autoAlpha: 0,
        x: 60,
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,
      }, 6)
    });

    const iconsRightT6 = gsap.timeline();
    const iconsRight6 = document.querySelectorAll('.icon--right-6');
    ScrollTrigger.create({
      animation: iconsRightT6,
      start: "31%",
      end: '40%',
      scrub: 3
    });
    iconsRight6.forEach((e) => {
      iconsRightT6.fromTo(e, {
        autoAlpha: 0,
        x: 50,
      }, {
        autoAlpha: 1,
        x: 0,
        duration: 2,

      }, 6)
    });
    const last = gsap.timeline();
    ScrollTrigger.create({
      animation: last,
      start: "50%",
      end: '100%',
      scrub: 1,
      onEnter: () => {
        document.getElementsByClassName('section--basic')[0].classList.remove('fixed');
        serverBus.$emit('finished');
        console.log('1')
      }
    });
    last.play();
  }
}
</script>