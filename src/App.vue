<template>
<div id="app">
  <Statue/>

</div>
  
</template>

<script>
import Painting from './components/Painting.vue'
import Statue from './components/Statue.vue'
export default {

  
  name: 'App',
  components: {
    Painting,
    Statue
  },
  data() {
    return {
      festmeny_on: true,
    }
  },
  methods: {
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
