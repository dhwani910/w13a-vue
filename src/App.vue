<template>
  <div id="app">
    <vue-menu></vue-menu>
    <vue-header></vue-header>
    <vue-body></vue-body>
    <vue-footer></vue-footer>
  
    
    <img alt="Vue logo" src="./assets/logo.png">
    
  </div>
</template>

<script>

import VueMenu from './components/Menu.vue';
import VueHeader from './components/Header.vue';
import VueBody from './components/Body.vue';
import VueFooter from './components/Footer.vue';




export default {
  name: 'App',
  components: {
    
    VueMenu,
    VueHeader,
    VueBody,
    VueFooter,
    
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
  margin-top: 60px;
}
</style>
