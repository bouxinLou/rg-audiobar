<template>
  <div id="app">
    <hello-world />
  </div>
</template>

<script>
import RugooAudioPlayer from "@/components/rg-audio-player";
import HelloWorld from "@/components/HelloWorld";

export default {
  name: 'App',
  components: {
    RugooAudioPlayer,
    HelloWorld
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
