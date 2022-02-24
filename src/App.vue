<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <alert></alert>
  </div>
</template>

<script>
import alert from './views/alert.vue'

export default {
  name: 'App',
  components: {
    alert
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
