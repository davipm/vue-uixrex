<template>
  <div class="home">
    <Hero/>
    <About @showConsole="showConsole"/>
    <Feature/>
    <Pricing/>
    <Screenshot/>
    <Clients/>
    <Contact/>
    <Map/>
  </div>
</template>

<script>
  // @ is an alias to /src
  import Hero from '@/components/Hero'
  import About from '../components/About'
  import Feature from '../components/Features'
  import Pricing from '../components/Pricing'
  import Screenshot from '../components/Screenshot'
  import Clients from '../components/Clients'
  import Contact from '../components/Contact'
  import Map from '../components/Map'

  export default {
    name: 'home',
    components: {
      Hero,
      About,
      Feature,
      Pricing,
      Screenshot,
      Clients,
      Contact,
      Map
    },

    methods: {
      showConsole() {
        console.log('Event component test')
      }
    }
  }
</script>
