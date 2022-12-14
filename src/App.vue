<template>
 <div>
  <Navbar/>
  <Foter />
  <router-view />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Foter from './components/foter.vue'

  export default {
    components:{
      Navbar,
      Foter
    }
  }

</script>

<style>

</style>
