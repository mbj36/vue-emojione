<template>
  <div id="app">
    <emojione></emojione>
  </div>
</template>

<script>
  import Emojione from './components/Emojione.vue';

  export default {
    name: 'app',
    components: {
      Emojione
    }
  };
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
