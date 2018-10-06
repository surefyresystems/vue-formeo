<template>
  <div id="app">
    <vue-formeo>
    </vue-formeo>
  </div>
</template>

<script>
//import VueFormeo from './components/vue-formeo.vue'
import VueFormeo from './components/vue-formeo.vue'

export default {
  name: 'app',
  components: {
    VueFormeo
  }
}
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
