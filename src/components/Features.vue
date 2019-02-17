<template>
  <section class="section feature">
    <div class="container">
      <h3 class="title">Features The App</h3>
      <p class="text">
        Writers and stars of Veep have responded incredulously to the news an Australian politician
        required preinstalled stitches way  email client, calendar, mapping program.
      </p>
      <div class="row">
        <div class="col-lg-4 col-md-12">
          <div class="image-example">
            <img src="../assets/images/image-example.png" class="img-feature" alt="">
          </div>
        </div>
        <div class="col-lg-8 col-md-12">
          <div class="content-feature">
            <div class="media" v-for="(item, index) in feature" :key="index">
              <img :src="item.img" class="media-icon mr-3" :alt="item.alt">
              <div class="media-body">
                <h5 class="media-title">{{ item.title }}</h5>
                <p class="media-text" v-text="item.text"></p>
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
    name: 'Features',
    data() {
      return {
        feature: [
          {
            img: 'https://via.placeholder.com/60',
            title: 'Media heading',
            alt: 'image title',
            text: `
            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque
            ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra
            turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.`
          },
          {
            img: 'https://via.placeholder.com/60',
            title: 'Media heading',
            alt: 'image title',
            text: `
            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque
            ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra
            turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.`
          },
          {
            img: 'https://via.placeholder.com/60',
            title: 'Media heading',
            alt: 'image title',
            text: `
            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque
            ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra
            turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.`
          },
          {
            img: 'https://via.placeholder.com/60',
            title: 'Media heading',
            text: `
            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque
            ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra
            turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.`
          },
        ]
      }
    }
  }
</script>

<style scoped lang="scss">
  .feature {
    display: block;
    position: relative;
    padding: 60px 0 200px 0;
    background: #F8F6F6 url("../assets/images/feature-bg.svg") 0 101% no-repeat;
    @media (max-width: 768px) {
      background-position: 35% 0;
      background-size: 350%;
    }
    @media (max-width: 576px) {
      background-position: 35% 0;
      background-size: 800%;
    }
  }

  .title {
    margin-bottom: 40px;
    color: #FFF;
    font-size: 36px;
    text-align: center;
  }

  .text {
    margin-right: auto;
    margin-left: auto;
    margin-bottom: 50px;
    width: 70%;

    color: #FFF;
    text-align: center;
  }

  .content-feature {
    padding-left: 40px;
  }

  .img-feature {
    display: block;
    margin-left: auto;
    width: 75%;
    @media (max-width:768px) {
      width: 50%;
      margin: 0 auto 40px auto;
    }
  }

  .media {
    margin-bottom: 20px;
    color: #FFF;
    &-title {
      margin-bottom: 1rem;
    }
    &-text {
      font-size: 14px;
    }
  }
</style>