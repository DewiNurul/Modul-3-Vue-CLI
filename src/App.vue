<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <First msg="First Component"></First>
  </div>
</template>

<script>
import First from './components/First'

export default {
  name: 'app',
  components: {
    First
  }
}

// import HelloWorld from './components/HelloWorld.vue'

// export default {
//   name: 'App',
//   components: {
//     HelloWorld
//   }
// }
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
