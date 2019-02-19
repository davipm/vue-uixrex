<template>
  <section class="section contact">
    <div class="container">
      <h3 class="title">Say Hello To Us!</h3>
      <p class="text">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit,
        sed do eiusmod tempor incididunt ut labore. et dolore magna aliqua.
      </p>
      <div class="contact-content">
        <form action="" class="form">
          <div class="row">
            <div class="col-md-4">
              <address class="address">
                <div class="address-item">
                  <h5 class="address-title">
                    <span class="icon"><i class="fas fa-map-marker-alt"></i></span>
                    Location:
                  </h5>
                  <p class="address-text">Fortaleza/CE - Brazil</p>
                </div>
                <div class="address-item">
                  <h5 class="address-title">
                    <span class="icon"><i class="fas fa-phone"></i></span>
                    Tel:
                  </h5>
                  <p class="address-text">+1234321321</p>
                </div>
                <div class="address-item">
                  <h5 class="address-title">
                    <span class="icon">
                      <i class="fas fa-envelope"></i>
                    </span>
                     Email:
                  </h5>
                  <p class="address-text">websitename@mail.com</p>
                </div>
              </address>
            </div>
            <div class="col-md-8">
              <div class="form-group">
                <input type="text" class="form-control" placeholder="Name">
              </div>
              <div class="form-group">
                <input type="text" class="form-control" placeholder="Email">
              </div>
              <div class="form-group">
                <textarea name="nessage"
                          id="message"
                          class="form-control"
                          cols="30"
                          rows="10"
                          placeholder="Message"
                ></textarea>
              </div>
            </div>
          </div>
          <div class="btn-send text-center">
            <button class="btn btn-primary">Send Message</button>
          </div>
        </form>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Contact'
  }
</script>

<style scoped lang="scss">
  .contact {
    display: block;
    position: relative;
    padding: 60px 0;
    background-color: #F7F7F7;
  }

  .title {
    margin-bottom: 25px;
    font-size: 36px;
    text-align: center;
    &::after {
      content: '';
      display: block;
      position: relative;
      top: 6px;
      height: 2px;
      width: 100px;
      background-color: #226BE2;
      margin: auto;
    }
  }

  .text {
    margin-right: auto;
    margin-left: auto;
    margin-bottom: 50px;
    width: 70%;
    text-align: center;
  }

  .icon {
    display: inline-block;
    position: relative;
    width: 30px;
    font-size: 1.1rem;
  }

  .address {
    padding: 30px;
    background-color: #FFF;

    &-title {
      font-size: .9rem;
      font-weight: bold;
    }

    &-text {
      font-size: .8rem;
      text-indent: 36px;
    }
  }

  .form-control {
    border: none;
    border-radius: 0;
  }

  .btn-primary {
    color: #FFF;
    background-color: #226BE2;
    border-radius: 0;
  }
</style>