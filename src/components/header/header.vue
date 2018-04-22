<template>
  <div class="aj-header-main navbar navbar-inverse">
    <h1> Abey Joy </h1>
    <div class="aj-social-icons">
      <i class="fab fa-github"></i>
      <i class="fas fa-camera-retro"></i>
      <i class="fab fa-facebook-f"></i>
    </div>

  </div>
</template>

<script>

export default {
  components: {},
  computed: {}
}
</script>

<style lang="scss">
  .aj-header-main {
    // background: #000;
    h1 {
      padding: 15px;
      // color: #ef0d33;
      // color: white;
      display: inline-block;

    }
    .aj-social-icons {
      display: inline-block;
      position: absolute;
      right: 10px;
      top: 10px;
      i {
        padding: 5px;
      }
    }
    .fa-facebook-f {
      font-size: 2.6em;
      color: #3b5998;
    }
    .fa-github {
      font-size: 3em;
      color: grey;
    }
    .fa-camera-retro {
      display: inline-block;
      font-size: 3em;
      color: brown;
    }
  }
</style>
