<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="footer-content">
            <h5 class="footer-title">
              Copyright © 2018 UIXREX, All rights Reserved.
            </h5>
          </div>
        </div>
        <div class="col-md-6">
          <div class="social">
            <ul class="social-list">
              <li class="social-item">
                <a href="#" class="social-link"><i class="fab fa-facebook-f"></i></a>
              </li>
              <li class="social-item">
                <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
              </li>
              <li class="social-item">
                <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
  export default {
    name: 'Footer'
  }
</script>

<style scoped lang="scss">
  .footer {
    position: relative;
    display: block;
    padding: 40px 0;
    background-color: #13253B;
    color: #FFF;
    &-title {
      text-align: center;
      font-size: .9rem;
      margin-bottom: 0;
    }
  }

  .social-list {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0;
    margin: 0;
    list-style: none;
  }

  .social-link {
    display: block;
    margin-right: 40px;
    color: #FFF;
  }
</style>