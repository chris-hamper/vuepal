<template>
  <div id="app">
    <top-nav></top-nav>
  </div>
</template>

<script>
import TopNav from './components/TopNav';

export default {
  name: 'app',
  components: {
    TopNav,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
