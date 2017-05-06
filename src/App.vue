<template>
  
  <div id="app">
      <s4b-loader />
      <s4b-nav />
      <hello />

  </div>
</template>

<script>
import Hello from './components/Hello'
import Nav from './components/Nav'
import Loader from './components/Loader'

export default {
  name: 'app',
  components: {
    Hello,
    's4b-nav': Nav,
    's4b-loader': Loader
  }
}

</script>

<style>

    @import './../node_modules/bootstrap/dist/css/bootstrap.css';
    @import './../node_modules/bootstrap-vue/dist/bootstrap-vue.css';
    @import './assets/styles/adminnine_classic.css';

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
