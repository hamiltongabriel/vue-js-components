<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <task/>
  </div>
</template>

<script>
import HelloWorld from './components/tasks/task.vue'
import task from './components/tasks/task.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
    task
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
