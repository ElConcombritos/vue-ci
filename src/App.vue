<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Todo/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Todo from "@/components/Todo";

export default {
  name: 'App',
  components: {
    HelloWorld,
    Todo
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
