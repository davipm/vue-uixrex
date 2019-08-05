<template>
  <div id="app">
    <!-- header component -->
    <Header/>
    <!-- content render -->
    <router-view/>
    <!-- footer component -->
    <Footer/>
  </div>
</template>

<script>
  import Header from './components/Header'
  import Footer from './components/Footer'
  export default {
    name: 'App',
    components: {
      Header,
      Footer
    }
  }
</script>

<style lang="scss">
  html,
  body {
    margin: 0;
    padding: 0;
    font-family: 'Montserrat', sans-serif;
    font-size: 1rem;
    color: #5D5D5D;
  }
</style>
