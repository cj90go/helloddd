<template>
  <div id="app">
    <HelloDDD msg="Welcome"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import Index from "@/components/Index";
import HelloDDD from "@/components/HelloDDD";

export default {
  name: 'App',
  components: {
    // eslint-disable-next-line vue/no-unused-components
    // Index
    HelloDDD
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
