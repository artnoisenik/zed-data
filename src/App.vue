<template>
  <h1>Zed Data</h1>
  <ZedData msg="Making sense of digital horses."/>
</template>

<script>
import ZedData from './components/zed-data.vue'

export default {
  name: 'App',
  components: {
    ZedData
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
