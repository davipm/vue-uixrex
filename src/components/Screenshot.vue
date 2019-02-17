<template>
  <section class="section screenshot">
    <div class="container">
      <h3 class="title">App Screenshots</h3>
      <p class="text">
        Most such devices are sold with several apps bundled as pre-installed software,
        such as a web browser, email client, calendar, mapping program.
      </p>
    </div>
    <div class="container-fluid">
      <div class="screenshot-content">
        <carousel :responsive="{ 0: {items: 1,nav: false}, 768: {items: 3, nav: false}, 960: {items: 4, nav: false}}" :nav="false">
          <img src="../assets/images/screen-1.png" class="screenshot-img" alt="">
          <img src="../assets/images/screen-2.png" class="screenshot-img" alt="">
          <img src="../assets/images/screen-3.png" class="screenshot-img" style="height: 671px;" alt="">
          <img src="../assets/images/screen-4.png" class="screenshot-img" alt="">
          <img src="../assets/images/screen-1.png" class="screenshot-img" alt="">
          <img src="../assets/images/screen-2.png" class="screenshot-img" alt="">
          <img src="../assets/images/screen-3.png" class="screenshot-img" style="height: 671px;" alt="">
          <img src="../assets/images/screen-4.png" class="screenshot-img" alt="">
          <template slot="prev"><span class="btn-screen prev"><i class="fas fa-arrow-left"></i></span></template>
          <template slot="next"><span class="btn-screen next"><i class="fas fa-arrow-right"></i></span></template>
        </carousel>
      </div>
    </div>
  </section>
</template>

<script>
  import carousel from 'vue-owl-carousel'
  export default {
    name: 'Screenshot',
    components: {
      carousel,
    }
  }
</script>

<style scoped lang="scss">
  .screenshot {
    display: block;
    position: relative;
    padding: 60px 0;
  }

  .title {
    margin-bottom: 40px;
    font-size: 36px;
    text-align: center;
  }

  .text {
    margin-right: auto;
    margin-left: auto;
    margin-bottom: 50px;
    width: 70%;
    text-align: center;
  }

  .screenshot-content {
    margin-top: 30px;
  }
</style>

<style lang="scss">
  span[id^="carousel_next"] {
    position: absolute;
    display: inline-block!important;
    left: 52%;
  }

  span[id^="carousel_prev"] {
    position: absolute;
    display: inline-block!important;
    bottom: 15px;
    left: 45%;
    @media (max-width:576px) {
      left: 35%;
    }
  }

  .btn-screen {
    display: inline-block;
    width: 45px;
    height: 45px;
    padding-top: 8px;
    text-align: center;
    font-size: 19px;
    color: #FFF;
    background-color: #4085F6;
    border-radius: 50%;
    cursor: pointer;
    border: 1px solid transparent;
    -webkit-transition: all .15s ease-in-out;
    -moz-transition: all .15s ease-in-out;
    -ms-transition: all .15s ease-in-out;
    -o-transition: all .15s ease-in-out;
    transition: all .15s ease-in-out;
    &:hover {
      color: #4085F6;
      background-color: transparent;
      border-color: #4085F6;
    }

    &:active {
      color: #FFF;
      background-color: #4085F6;
    }
  }

  @media (max-width: 768px) {
    .screenshot-img {
      height: auto!important;
    }
  }
</style>