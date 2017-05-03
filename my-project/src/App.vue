<template>
  <div id="app">

      <ui-button color="primary">Primary button</ui-button>
      <ui-button color="accent">Accent button</ui-button>

  </div>
</template>

<script>
  import 'keen-ui/src/bootstrap'; // Required to setup Keen UI, should be imported only once in your project
  import UiButton from 'keen-ui/src/UiButton.vue';
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    UiButton
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
