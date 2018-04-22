<template>
  <div id="app">
    <Header></Header>
  </div>
</template>

<script>
import Header from './components/header/header.vue'

export default {
  components: {
    Header: Header
  },
  mounted() {
    console.log('hi')
  }
}
</script>

<style lang="scss">

</style>
