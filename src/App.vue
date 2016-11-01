<template>
  <div id="app">
    <img src="./assets/logo.png" >
    <hello></hello>
    <notes></notes>
  </div>
</template>

<script>
import Hello from './components/Hello';
import Notes from './components/Notes';

export default {
  name: 'app',
  components: {
    Hello,
    Notes,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smootPhing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
