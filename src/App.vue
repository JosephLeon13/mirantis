<template>
  <div id="app">
    <Nav />
    <router-view/>
    <Footer />
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    Nav,
    Footer
  },
  data() {
    return {
      
    }
  },
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
@import url('https://fonts.googleapis.com/css?family=Montserrat:700&display=swap');

#app {
  font-family: 'Montserrat', sans-serif;
  color: #000;
  line-height: 1.8;
}
</style>
