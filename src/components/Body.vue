<template>
<main>
<h1> Body</h1>  

  <vue-side-panel></vue-side-panel>
  <vue-code-example></vue-code-example>
   <vue-meet-team></vue-meet-team>
</main>
</template>

<script>


import VueSidePanel from './SidePanel.vue';
import VueCodeExample from './CodeExample.vue';
import VueMeetTeam from './MeetTeam.vue';



export default{
    name: 'VueBody',
    components: {
        VueSidePanel,
        VueCodeExample,
        VueMeetTeam
    }
}

</script>

<style scoped>

</style>