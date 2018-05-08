<template>
  <div id="app">
    <Intro></Intro>
  </div>
</template>

<script>

import Intro from './components/intro/intro.vue'

export default {
  components: {
    Intro: Intro
  },
  mounted() {
    console.log('hi')
  }
}
</script>

<style lang="scss">
  #app {
    background-color: #282a36;
  }
</style>
