<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <el-button type="primary">主要按钮</el-button>
    <test></test>
  </div>
</template>

<script>
export default {
  name: 'App',
  components:{
    test
  }
}

import test from './components/test.vue'
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
