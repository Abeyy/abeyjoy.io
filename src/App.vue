<template>
  <div id="app">
    <Header></Header>
    <Skills></Skills>
  </div>
</template>

<script>
import Header from './components/header/header.vue'
import Skills from './components/skills/skills.vue'
export default {
  components: {
    Header: Header,
    Skills: Skills
  },
  mounted() {
    console.log('hi')
  }
}
</script>

<style lang="scss">

</style>
