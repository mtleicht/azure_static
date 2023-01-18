<template>
  <NavigationHeader/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome2"/>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import NavigationHeader from './components/NavigationHeader.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,NavigationHeader
  }
}
</script>

<style>
#app {
  font-family: sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body{

}
</style>
