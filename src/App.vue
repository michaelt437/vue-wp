<template>
  <div id="app">
    <img src="./assets/logo.png" alt="">
    <router-link to="/">Home</router-link>
    <router-link to="/components/Buttons">Buttons</router-link>
    <router-link to="/components/Forms">Forms</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
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
