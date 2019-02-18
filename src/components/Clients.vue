<template>
  <section class="section clients">
    <div class="container">
      <h3 class="title">SOME TALK OF OUR CLIENTS</h3>
      <div class="clients-slide">
        <carousel :responsive="{ 0: {items: 1,nav: false}, 768: {items: 1, nav: false}, 960: {items: 2, nav: false}}" :nav="false">
          <div class="card">
            <img src="../assets/images/client-1.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../assets/images/client-2.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../assets/images/client-1.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../assets/images/client-2.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../assets/images/client-1.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../assets/images/client-2.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../assets/images/client-1.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
          <div class="card">
            <img src="../assets/images/client-2.png" class="card-client-thumb" alt="">
            <div class="card-body">
              <div class="card-info">
                <h6 class="client-name">OLIVER GOMEZ</h6>
                <p class="client-position">CEO of google</p>
              </div>
              <p class="card-text">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,good.
              </p>
            </div>
          </div>
        </carousel>
      </div>
    </div>
  </section>
</template>

<script>
  import carousel from 'vue-owl-carousel'
  export default {
    name: 'Clients',
    components: {
      carousel,
    }
  }
</script>

<style scoped lang="scss">
  .clients {
    display: block;
    position: relative;
    padding: 60px 0;
    background-color: #4085F6;
  }

  .title {
    margin-bottom: 15px;
    font-size: 32px;
    text-align: center;
    color: white;
    font-family: 'Montserrat', sans-serif;
    font-weight: 500;
  }

  .card {
    display: block;
    width: 95%;
    max-height: 285px;
    margin: 75px auto 0 auto;
    text-align: center;
    color: #FFF;
    border: 1px solid #FFF;
    background-color: transparent;

    &-body {
      position: relative;
      bottom: 60px;
      padding-left: 57px;
      padding-right: 57px;
    }

    &-text {
      text-align: left;
      font-size: 1rem;
    }
  }

  .owl-carousel .owl-item img {
    width: 122px;
    margin: auto;
    position: relative;
    bottom: 65px;
  }
</style>