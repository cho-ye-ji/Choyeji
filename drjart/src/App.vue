<template>
  <header>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </header>
  <section class="sec1">
    <div class="sec1_right">
      <p> right </p>
      <p> section </p>
    </div>
    <div class="sec1_left"></div>
  </section>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainSlide from './components/slide/MainSlide.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MainSlide
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
