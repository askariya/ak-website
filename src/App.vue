<template>
  <div id="app">
    <Navigation></Navigation>
    <!-- <Projects></Projects> -->
    <router-view/>
  </div>
</template>

<script>
import Navigation from './components/Navigation'
import Projects from './components/Projects'
export default {
  name: 'App',
  components: {
    'Navigation': Navigation,
    'Projects': Projects
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
}
</style>
