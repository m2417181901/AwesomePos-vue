<template>
  <div id="app">
    <Left-nav></Left-nav>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
import leftNav from '@/components/common/leftNav'
import LeftNav from './components/common/leftNav/index.vue'
export default {
    name: "App",
    comments: {
        leftNav
    },
    components: { LeftNav }
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
