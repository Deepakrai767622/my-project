<template>
  <div id="app">
    <Navbar />
    <h1>{{ title }}</h1>
     
  </div>
</template>

<script>

import Navbar from './components/Navbar'

export default {
  name: "app",
  components: {
    Navbar
  },
  data () {
    return{
      title: 'my first vue app, WOW :) '
    }
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
