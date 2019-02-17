<template>
  <section class="section pricing">
    <div class="container">
      <h3 class="title">Features The App</h3>
      <p class="text">
        Writers and stars of Veep have responded incredulously to the news an Australian politician
        required preinstalled stitches way  email client, calendar, mapping program.
      </p>
      <div class="pricing-content">
        <div class="row">
          <div class="col-lg-4 col-md-6">
            <div class="card">
              <ul class="pricing-list">
                <li class="pricing-list-title">Basic</li>
                <li class="pricing-list-value">$00</li>
                <li class="pricing-list-access">Limited access</li>
                <li class="pricing-list-item">100 MB Disk Space</li>
                <li class="pricing-list-item">2 Subdo mains</li>
                <li class="pricing-list-item">5 Email Accounts</li>
                <li class="pricing-list-item">No License</li>
                <li class="pricing-list-item">Phone & Mail Support</li>
                <li class="pricing-list-button">
                  <a href="#" class="btn btn-primary">PURCHASE</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="card">
              <ul class="pricing-list">
                <li class="pricing-list-title">Professional</li>
                <li class="pricing-list-value">$12</li>
                <li class="pricing-list-access">Limited access</li>
                <li class="pricing-list-item">100 MB Disk Space</li>
                <li class="pricing-list-item">2 Subdo mains</li>
                <li class="pricing-list-item">5 Email Accounts</li>
                <li class="pricing-list-item">No License</li>
                <li class="pricing-list-item">Phone & Mail Support</li>
                <li class="pricing-list-button">
                  <a href="#" class="btn btn-primary">PURCHASE</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="card">
              <ul class="pricing-list">
                <li class="pricing-list-title">Business</li>
                <li class="pricing-list-value">$22</li>
                <li class="pricing-list-access">Limited access</li>
                <li class="pricing-list-item">100 MB Disk Space</li>
                <li class="pricing-list-item">2 Subdo mains</li>
                <li class="pricing-list-item">5 Email Accounts</li>
                <li class="pricing-list-item">No License</li>
                <li class="pricing-list-item">Phone & Mail Support</li>
                <li class="pricing-list-button">
                  <a href="#" class="btn btn-primary">PURCHASE</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Pricing'
  }
</script>

<style scoped lang="scss">
  .pricing {
    display: block;
    position: relative;
    padding: 60px 0;
    background-color: #F8F6F6;
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

  .pricing-content {
    display: block;
    position: relative;
    width: 80%;
    margin: auto;
  }

  .card {
    border: 2px solid #226BE2;
    border-radius: 15px;
    cursor: pointer;
    background-color: #F8F6F6;
    -webkit-transition: all .15s ease-in-out;
    -moz-transition: all .15s ease-in-out;
    -ms-transition: all .15s ease-in-out;
    -o-transition: all .15s ease-in-out;
    transition: all .15s ease-in-out;
    &:hover {
      color: #FFF;
      background-color: #226BE2;
      .btn-primary {
        background-color: #fff;
      }
      .pricing-list-value {
        color: #FFF;
      }
    }
  }

  .pricing-list {
    margin: 0;
    padding: 0;
    text-align: center;
    list-style: none;
    &-title {
      margin: 20px 0;
    }
    &-value {
      margin-bottom: 20px;
      font-size: 2rem;
      color: #4085F6;
    }
    &-access {
      margin-bottom: 30px;
    }
    &-item {
      margin-bottom: 5px;
      font-size: 13px;
    }
  }

  .btn-primary {
    margin-top: 20px;
    margin-bottom: 20px;
    padding: 5px 40px;
    color: #226BE2;
    background-color: transparent;
    border: 2px solid #226BE2;
    border-radius: 20px;
  }

  @media (max-width: 768px) {
    .card {
      margin-bottom: 15px;
    }
  }
</style>