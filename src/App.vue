<template>
  <NavigationHeader/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome2"/>
  <NavigationFooter/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import NavigationHeader from './components/NavigationHeader.vue';
import NavigationFooter from './components/NavigationFooter.vue';

export default {
  name: 'App',
  components: {
    HelloWorld, NavigationHeader, NavigationFooter
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
