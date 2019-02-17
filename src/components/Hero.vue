<template>
  <section class="hero">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-md-12">
          <div class="img-content">
            <img src="../assets/images/phone.png" class="w-100" alt="">
          </div>
        </div>
        <div class="col-lg-6 col-md-12">
          <div class="hero-content">
            <div class="hero-body">
              <h1 class="hero-title">The Best App to Increase</h1>
              <h1 class="hero-title">Your Productivity</h1>
              <div class="hero-text">
                <p>A mobile app is a computer program designed to run on a</p>
                <p>mobile device such as a phone/tablet or watch.</p>
              </div>
              <div class="button-download">
                <a href="#" class="download-btn apple-play">
                  <img src="../assets/images/app-store.svg" class="img-fluid" alt="">
                </a>
                <a href="#" class="download-btn google-play">
                  <img src="../assets/images/play-store.png" class="img-fluid" alt="">
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Hero'
  }
</script>

<style scoped lang="scss">
  .hero {
    padding: 60px 0;
    height: 100%;
    background: url("../assets/images/hero-bg.png") 35% 104%/210% no-repeat border-box;
  }

  .hero-content {
    padding-top: 200px;
    text-align: right;
    color: #FFF;
  }

  .hero-text {
    margin-top: 30px;
    p {
      margin-bottom: .3rem;
    }
  }

  .button-download {
    margin-top: 50px;
    text-align: center;
  }

  .download-btn {
    display: inline-block;
    width: 200px;
    margin-right: 20px;
    &:last-child {
      margin-right: 0;
    }
  }

  @media (max-width: 768px){
    .hero {
      background: url("../assets/images/hero-bg.png") 52% 101%/264% no-repeat border-box;
    }

    .hero-content {
      padding-top: 0;
    }
  }

  @media (max-width: 576px) {
    .hero {
      background-position: 47% -78px;
      background-size: 341%;
    }

    .download-btn {
      margin-right: 0;
      margin-bottom: 15px;
    }
  }
</style>