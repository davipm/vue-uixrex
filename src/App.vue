<template>
  <div id="app">
    <Header/>
    <router-view/>
  </div>
</template>

<script>
  import Header from './components/Header'
  export default {
    name: 'App',
    components: {
      Header
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
