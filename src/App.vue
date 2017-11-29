<template>
  <div id="app">
    <fristcomponent></fristcomponent>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
import fristcomponent from './components/firstcomponent.vue'
export default {
  name: 'app',
  components: { fristcomponent }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
