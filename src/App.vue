<template>
  <div id="app">
    <helleWorld />
    <banner />
    <!--<helloTwo />-->
    <!--<helloThree />-->
    <!--<list/>-->
  </div>
</template>

<script>
import '@/assets/scss/common.css'
import HelleWorld from '@/components/HelloWorld'
import HelloTwo from '@/components/HelloTwo'
import HelloThree from '@/components/HelloThree'
import List from '@/components/list'
import Banner from '@/components/Banner'

export default {
  name: 'App',
  components: {
    HelleWorld,
    HelloTwo,
    HelloThree,
    List,
    Banner
  }
}
</script>

<style>

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: #fff;
  min-height: 100vh;
}
</style>
