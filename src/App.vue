<template>
  <v-app>
    <v-app-bar flat max-height="65">
      <navbar />
    </v-app-bar>

    <router-view></router-view>

    <v-footer>
      <Footer />
    </v-footer>
  </v-app>
</template>

<script>

import Navbar from './components/Navbar.vue'
import Footer from "./components/Footer.vue";

export default {
  name: 'App',
  components:{
    Navbar,
    Footer
  }
  
}
</script>

<style>


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}

</style>
