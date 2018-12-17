<template>
  <div id="app">
    <div class="flex">
      <div class="flex-1 text-center bg-white px-4 py-2 m-2"><img src="./assets/logo.png" /></div>
    </div>
    <router-view/>
  </div>
</template>

<script>
import '@/assets/css/main.css'

export default {
  name: 'App'
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
