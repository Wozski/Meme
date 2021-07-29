<template>
  <img id="home" alt="meme logo" src="https://memeprod.sgp1.digitaloceanspaces.com/user-wtf/1581611699409.jpg">
  <HelloWorld msg="Meme 大全"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Roboto,-apple-system,Helvetica Neue,Helvetica,Arial,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  min-width: 100px;
  min-height: 100vh;
  line-height: 1.5;
  font-size: 14px;
  margin: 0;
  box-sizing: border-box;
  border: 1px solid black;
  background-color: #000000;
}
img {
  max-width: 90%;
  height: auto;
  border: 2px solid white;
}
</style>
