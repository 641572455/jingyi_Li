<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
     <Hi/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Hi from './components/Hi.vue'
export default {
  name: 'App',
  data:{
    return{
      name:'dsafaf'
    }
  },
  components: {
    HelloWorld,Hi
  }
}
</script>

<style>

</style>
