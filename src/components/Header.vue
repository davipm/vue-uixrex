<template>
  <header class="header">
    <nav class="navbar navbar-expand-lg">
      <div class="container">
        <router-link class="navbar-brand" to="/">UIXREX</router-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about">
                About
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/page/feature">Features</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/page/pricing">Pricing</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/page/screenshot">Screenshot</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/page/contact">Contact</router-link>
            </li>
          </ul>
        </div>
        <div class="btn-try">
          <a href="#" class="btn btn-primary">Try For Free</a>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
  export default {
    name: 'Header',
    data() {
      return {

      }
    }
  }
</script>

<style scoped lang="scss">
  .header {
    position: absolute;
    display: block;
    width: 100%;
    background: transparent;
    z-index: 1;
  }

  .navbar {
    padding-top: 35px;
    padding-bottom: 35px;
  }

  .nav-link {
    display: inline-block;
    margin-right: 20px;
    font-weight: normal;
    font-style: normal;
    color: #FFF;
  }

  .navbar-brand {
    display: inline-block;
    margin-right: 80px;
    color: #FFF;
  }

  .btn-primary {
    padding: 10px 35px;
    color: #4085F6;
    background-color: #FFF;
    border-radius: 30px;
    -webkit-transition: all .15s ease-in-out;
    -moz-transition: all .15s ease-in-out;
    -ms-transition: all .15s ease-in-out;
    -o-transition: all .15s ease-in-out;
    transition: all .15s ease-in-out;
    &:hover {
      color: #FFF;
      background-color: transparent;
      border-color: #FFF;
    }
  }
</style>