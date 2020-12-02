<template>
  
  <div id="app">
    <Relationship/> 
  </div>
</template>

<script>
import Relationship from './components/Relationship.vue'
export default {
  name: 'App',
  components: {
    Relationship
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
</style>
