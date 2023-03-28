<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Section1nav/>
    <Section2/>
    <Section3/>
    <section4carrousel/>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import section1nav from './components/section1-nav.vue'
import section2 from './components/section2.vue'
import section3 from './components/section3.vue'
import section4carrousel from './components/section4-carrousel.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Section1nav,
    Section2,
    Section3,
    Section4carrousel
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
