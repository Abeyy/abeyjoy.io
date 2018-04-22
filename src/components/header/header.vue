<template>
  <div class="aj-header-main navbar navbar-inverse">
    <div class="aj-social-icons row">
      <a href="https://github.com/Abeyy/"><i class="fab fa-github"></i></a>
      <a href="https://www.instagram.com/abeyjjoy/"><i class="fas fa-camera-retro"></i></a>
      <a href="https://www.facebook.com/abey.j.joy"><i class="fab fa-facebook-f"></i></a>
    </div>
    <div class="aj-header-text row">
      <div class="col-md-3 col-lg-3 col-xl-3"></div>
      <div class="col-xs-12 col-s-12 col-md-6 col-lg-6 col-xl-6">
        Web developer with a proven track record of shipping clean, re-usable
        code. Currently disrupting how you shop as a Product Engineer at
        <a href="https://www.mikmak.tv"> MikMak.tv</a>

      </div>
      <div class="col-md-3 col-lg-3 col-xl-3"></div>

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
    background: url('https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/aj-bg-1.gif?alt=media&token=be7c1fdd-fe5d-42f4-a1ac-453519815d7f') no-repeat;
    background-size: 100% 100%;
    height: 100vh;
    h1 {
      padding: 10px;
      display: inline-block;
    }
    .aj-social-icons {
      display: inline-block;
      position: absolute;
      padding: 10px;
      right: 10px;
      top: 10px;
      i {
        padding: 5px;
      }
    }
    .fa-facebook-f {
      font-size: 3em;
      color: #3b5998;
      &:hover {
        opacity: 0.5;
      }
    }
    .fa-github {
      font-size: 3em;
      color: grey;
      &:hover {
        color: black;
      }
    }
    .fa-camera-retro {
      display: inline-block;
      font-size: 3em;
      color: brown;
      &:hover {
        color: red;
      }
    }
  }

  .aj-header-text {
    font-size: 36px;
    color: white;
    // width: 50%;
    // margin-left: 25%;
    text-shadow: 1px 1px #666;
  }
</style>
