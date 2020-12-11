<template>
  <div id="app">
    <vue-menu></vue-menu>
    <vue-header></vue-header>
    <vue-body></vue-body>
    <vue-footer></vue-footer>
    <vue-side-panel></vue-side-panel>
    <vue-code-example></vue-code-example>
    <vue-meet-team></vue-meet-team>
    
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Hello World"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import VueMenu from './components/Menu.vue';
import VueHeader from './components/Header.vue';
import VueBody from './components/Body.vue';
import VueFooter from './components/Footer.vue';
import VueSidePanel from './components/SidePanel.vue';
import VueCodeExample from './components/CodeExample.vue';
import VueMeetTeam from './components/MeetTeam.vue';



export default {
  name: 'App',
  components: {
    HelloWorld,
    VueMenu,
    VueHeader,
    VueBody,
    VueFooter,
    VueSidePanel,
    VueCodeExample,
    VueMeetTeam
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
