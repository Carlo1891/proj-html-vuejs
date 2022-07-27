<template>
  <div id="app">

    <Header />
    <Main />
    <Footer />
    
  </div>
</template>

<script>

  import Header from './components/macro/Header.vue';
  import Main from './components/macro/Main.vue';
  import Footer from './components/macro/Footer.vue';

  export default {
    name: 'App',
    components: {
    Header,
    Main,
    Footer
    }
  }

</script>

<style lang="scss">

  @import "./assets/styles/variables.scss";
  @import "~bootstrap/dist/css/bootstrap.css";
  @import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css");

</style>
