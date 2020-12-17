<template>
  <div id="nav">
    <p>Đây là App</p>
  </div>
<todos />
  <router-view/>
</template>
<script>
import Todos from './components/Todos.vue'
export default {
  components: { Todos },
  
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

</style>
