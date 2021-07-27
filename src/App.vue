<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <badge text="Test" type="primary" />
    <cards />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Badge from './components/badge.vue'
import Cards from './components/cards.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Cards,
    Badge
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
