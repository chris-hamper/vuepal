<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <ul>
      <li><a href="a" target="_blank">Core Docs</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'top-nav',
  data() {
    return {
      title: 'Vuepal',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  ul {
    display: inline-block;
    list-style-type: none;
    padding: 0;
  }

  h1, li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
    text-decoration: none;
  }
</style>
