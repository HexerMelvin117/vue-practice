<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to my App"/>
  <TestComp titleMessage="This look pretty cool" />
  <ListComp />
  <CounterComp />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TestComp from './components/TestComp.vue'
import ListComp from './components/ListComp.vue'
import CounterComp from './components/CounterComp.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TestComp,
    ListComp,
    CounterComp
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
