<template>
  <div id="app">
    <mainpage></mainpage>
  </div>
</template>

<script>
import mainpage from './components/mainPage'

export default {
  name: 'App',
  components: {
    mainpage
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
