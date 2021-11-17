<template>
  <div class="banner container-fluid">
    <div class="banner-text">
      <div class="inner-text">
        <h1>"如果海會說話，如果你愛上浪"</h1>
        <h3>預約一場與大海的約會</h3>
        <div class="banner-btn">
          <i class="fas fa-angle-double-right"></i>
          <router-link class="btn topic-color text-light" to="/products">預約衝浪</router-link>
          <i class="fas fa-angle-double-left"></i>
        </div>
      </div>
    </div>
  </div>
  <div class="container my-5">
    <h1 class="index text-center animate__animated wow animate__rubberBand">
      台灣浪點推薦
    </h1>
  </div>
  <div class="container-fluid p-0">
    <div class="attractions d-flex">
      <div class="img-intro img1 animate__animated wow animate__fadeIn"></div>
      <div class="introduce p-3">
        <h3 class="text-light">烏石港</h3>
        <p class="text-light animate__animated wow animate__bounceInRight">烏石港幾乎是連不衝浪的人都知道的浪點了！良好的地理位置提供了足夠的能量，無論是什麼樣的板型都有適合的浪衝！沿著整個海提也有許多租浪板與提供教學的店家，即使是衝浪新手也不用害怕不知道從何而起！</p>
      </div>
    </div>
    <div class="attractions d-flex">
      <div class="introduce p-3">
        <h3 class="text-light">漁光島</h3>
        <p class="text-light  animate__animated wow animate__bounceInLeft">浪點為位於以前秋茂園旁馬場的後方沙灘，雖然秋茂園已荒廢，但現在的漁光島因海灘漂亮又可進行衝浪、風帆、帆船、獨木舟等水上活動，假日遊客多。</p>
      </div>
      <div class="img-intro img2 animate__animated wow animate__fadeIn"></div>
    </div>
    <div class="attractions d-flex">
      <div class="img-intro img3 animate__animated wow animate__fadeIn"></div>
      <div class="introduce p-3">
        <h3 class="text-light">佳樂水</h3>
        <p class="text-light  animate__animated wow animate__bounceInRight">佳樂水距離南灣大約半小時的車程，會來到這邊的人幾乎都是為了衝浪而來的！因為河口地形讓這禮儀年四季都有浪可以衝，再加上墾丁四季如夏的天氣幾乎沒有不能衝的季節！</p>
      </div>
    </div>
  </div>
  <div class="container shop-event text-center my-5">
      <div class="display-1">慶祝開幕</div>
      <div class="mb-3 h3">立即使用9折優惠碼</div>
      <div class="h3 mb-2">優惠碼:open0726</div>
      <router-link class="btn topic-color mb-2" to="/products">預約衝浪</router-link>
  </div>
</template>

<script>
import { WOW } from 'wowjs'
export default {
  mounted () {
    new WOW({ live: false }).init()
  }
}
</script>
