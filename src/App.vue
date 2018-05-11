<template>
  <div id="app">
    <div class="">
        <Intro></Intro>
    </div>

    <Background></Background>
  </div>
</template>

<script>

import Intro from './components/intro/intro.vue'
import Background from './components/background/background.vue'

export default {
  components: {
    Intro: Intro,
    Background: Background
  },
  mounted() {}
}
</script>

<style lang="scss">
  #app {
    background-color: #282a36;
  }
</style>
