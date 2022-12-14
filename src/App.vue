<template>
 <div>
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view />
  <Foter />
  
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Foter from './components/foter.vue'

  export default {
    components:{
      Navbar,
      Foter
    },
    data() {
      return {
        logo_src: '/img/logo.png',
        app_name: 'stake'
      }
    },
  }

</script>

<style>
 * {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  .main-container {
    margin: 50px;
    min-height: 551px;
  }
  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 50px;
    color: #222;
  }
</style>
