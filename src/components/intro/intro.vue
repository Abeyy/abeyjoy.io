<template>
  <div class="intro">
    <div class="aj-header-links">
      <a href="#"> Resume </a>
      <a href="https://github.com/Abeyy"> GitHub </a>
      <a href="https://www.linkedin.com/in/abey-joy-02385085/"> LinkedIn </a>
      <a href="https://www.instagram.com/abeyjjoy/"> Instagram </a>
    </div>
    <br>
    <br>
    <br>
    <div class="aj-header-text">
      <p> Hi! I'm <span>Abey.</span></p>
      <br>
        <p>I'm a design oriented software engineer with a proven track record of shipping clean, reusable
        code. Currently disrupting how you shop as a Product Engineer at
        <a href="https://www.mikmak.tv"> <span id="typed-string"></span></a>✌</p>
    </div>
    <div class="aj-email-header">
      Lets Collaborate: <a href="#">abey.joy21@gmail.com</a>
    </div>
  </div>
</template>

<script>
  import Typed from 'typed.js'

  export default {
    props: [],
    data() { return {} },
    components: {},
    mounted() {
      this.typeAnimator()
    },
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
    },
    watch: {}
  }

</script>

<style lang="scss">
  .intro {
    height: 100vh;
  }

  .aj-header-text {
    font-size: 36px;
    color: white;
    text-shadow: 1px 1px #666;
    width: 40%;
    letter-spacing: 1.5px;
    margin-left: 50px;
    padding: 3%;
  }

  .aj-email-header {
    font-size: 36px;
    color: white;
    text-shadow: 1px 1px #666;
    letter-spacing: 1.5px;
    margin-left: 50px;
    padding: 3%;
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
  .aj-header-links {
    float: right;
    padding: 10px;
  }
  .aj-header-links a {
    text-transform: uppercase;
    font-size: 18px;
    margin: 10px;
    color: white;
  }
</style>
