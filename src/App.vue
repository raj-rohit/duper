<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
  <Hero></Hero>
  </div>
</template>

<script>

import Hero from '../more/src/components/Hero'
export default {
  name: 'App',
  components: {
     Hero
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
