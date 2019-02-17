<template>
  <section class="section about">
    <div class="container">
      <h3 class="title">About The App</h3>
      <p class="text">
        Writers and stars of Veep have responded incredulously to the news an Australian politician
        required preinstalled stitches way  email client, calendar, mapping program.
      </p>
      <div class="row">
        <div class="col-lg-4 col-md-6">
          <div class="card shadow p-3 mb-5 bg-white rounded" @click="$emit('showConsole')">
            <img src="../assets/images/icon-1.svg" class="img-icon" alt="">
            <div class="card-body">
              <h5 class="card-title">24/7 Support</h5>
              <p class="card-text">
                Apps that are not preinstalled are usually available through distribution platforms called app stores.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="card shadow p-3 mb-5 bg-white rounded">
            <img src="../assets/images/icon-1.svg" class="img-icon" alt="">
            <div class="card-body">
              <h5 class="card-title">Data Privacy</h5>
              <p class="card-text">
                Apps that are not preinstalled are usually available through distribution platforms called app stores.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="card shadow p-3 mb-5 bg-white rounded">
            <img src="../assets/images/icon-1.svg" class="img-icon" alt="">
            <div class="card-body">
              <h5 class="card-title">Easy Download</h5>
              <p class="card-text">
                Apps that are not preinstalled are usually available through distribution platforms called app stores.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'About',
    data() {
      return {

      }
    },
  }
</script>

<style scoped lang="scss">
  .section {
    display: block;
    position: relative;
    padding: 40px 0;
  }

  .title {
    margin-bottom: 30px;
    font-size: 36px;
    font-weight: 500;
    text-align: center;
  }

  .text {
    margin-right: auto;
    margin-left: auto;
    margin-bottom: 50px;
    width: 70%;
    text-align: center;
  }

  .card {
    display: block;
    position: relative;
    text-align: center;
    border: none;
    &-title {
      display: block;
      margin-bottom: 2.5rem;
    }
    &-text {
      font-size: .8rem;
    }
  }

  .img-icon {
    display: block;
    margin: 20px auto;
  }

  .card-body {
    padding-bottom: 2.2rem;
  }
</style>