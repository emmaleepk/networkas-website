<template>
  <div id="app">
    <Home msg="Network America Services"/>
  </div>
</template>

<script>
import Home from './components/index.vue'

export default {
  name: 'App',
  components: {
    Home
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
  margin-top: 10px;
}
body {
  background: #FAF9F0
}
</style>
