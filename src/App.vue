<template>
  <div id="app">
    <Body class="body" />
    <particles-bg type="cobweb" color="#711c91" :num=30 :canvas="{backgroundColor:'#ffffff'}" :bg="true"/>
  </div>
</template>

<script>
import { ParticlesBg } from "particles-bg-vue";
import Body from "./components/Body.vue";
export default {
  name: "App",
  components: {
    Body,
    ParticlesBg
    
}
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: flex;
  min-height: 95vh;
}
</style>