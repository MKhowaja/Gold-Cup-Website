<template>
  <div id="app">
    <top-nav></top-nav>
    <router-view></router-view>
    <bottom-nav></bottom-nav>
  </div>
</template>

<script>
import TopNav from './components/TopNav.vue'
import BottomNav from './components/BottomNav.vue'
export default {
  name: 'app',
  components: {TopNav, BottomNav}
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
