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
        <a href="https://www.mikmak.tv"> <span id="typed-string"></span></a>
      </div>
      <div class="col-md-3 col-lg-3 col-xl-3"></div>
    </div>

    <div class="scrollText" v-show="showScroll">
      <i class="fas fa-arrow-down"></i> Scroll
    </div>
  </div>
</template>

<script>

import Typed from 'typed.js'



export default {
  data() {
    return {
      showScroll: false
    }
  },
  mounted() {
    this.scrollTimer()
    this.scrollHandler()
    this.typeAnimator()
  },
  components: {},
  computed: {},
  methods: {
    typeAnimator() {
      const options = {
        strings: ["MikMak.Tv"],
        typeSpeed: 50,
        backsSpeed: 50
      }

      var typed = new Typed('#typed-string', options)
    },
    scrollTimer() {
      setTimeout(() => {
        this.showScroll = true
      }, 7500)
    },
    scrollHandler() {
      let self = this
      window.addEventListener('scroll', function(e) {
        self.showScroll = false
      })
    }
  },
  watch: {}
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

  .scrollText {
    font-size: 36px;
    color: white;
    text-shadow: 1px 1px #666;
    position: absolute;
    right: 10px;
    bottom: 10px;
  }

  .typed-cursor{
  opacity: 1;
  animation: typedjsBlink 0.7s infinite;
  -webkit-animation: typedjsBlink 0.7s infinite;
  animation: typedjsBlink 0.7s infinite;
  }
  @keyframes typedjsBlink{
    50% { opacity: 0.0; }
  }
  @-webkit-keyframes typedjsBlink{
    0% { opacity: 1; }
    50% { opacity: 0.0; }
    100% { opacity: 1; }
  }
  .typed-fade-out{
    opacity: 0;
    transition: opacity .25s;
    -webkit-animation: 0;
    animation: 0;
  }
</style>
