<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <ul>
      <li><a href="#" target="_blank">Articles</a></li>
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
  h1, ul, li {
    display: inline-block;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  h1 {
    margin: 10px 20px 0;
  }

  li {
    margin: 0 10px 0;
    font-size: 120%;
  }

  a {
    color: #328c61;
    text-decoration: none;
  }

  .hello {
    background-color: #d8e4f0;
  }
</style>
