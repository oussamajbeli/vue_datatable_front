<template>
  <div id="app" class="container">
    <img alt="Vue logo" src="./assets/logo.png">
    <JqueryTable/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import JqueryTable from './components/JqueryTable.vue'

export default {
  name: 'App',
  components: {
    JqueryTable
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.container{
  max-width: 1000px;
}
</style>
