<template>
  <div class="aj-skills row">
    <!-- <div class="col-md-1 col-lg-1 col-xl-1"></div> -->

    <div class=" card-row card col-xs-12 col-s-12 col-md-3 col-lg-3 col-xl-3">
      <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skills-study.gif?alt=media&token=4c36fef0-8ced-4ac0-a64a-e365f902ca4d" alt="">
      <div class="card-body">
        <h5 class="card-title">Education</h5>
        <span class='nyu'>
          <img class='nyu-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/nyu.jpg?alt=media&token=d393b56b-a48e-4cfc-8c4d-dee5bbc1a196">
          <span class='nyu-header'> New York University</span>
          <div> Tandon School of Engineering</div>
          <div> B.S. Computer Engineering, <span class='nyu-date'>2016</span></div>
          <div> B.S. Electrical Engineering, <span class='nyu-date'>2017</span></div>
        </span>
      </div>
    </div>

    <div class="card col-xs-12 col-s-12 col-md-3 col-lg-3 col-xl-3">
      <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skill-programming.gif?alt=media&token=cb133233-e052-43a9-8e64-dd70807dec16" alt="">
      <div class="card-body">
        <h5 class="card-title">Programming Skills</h5>
      </div>
      Test
    </div>

    <div class="card col-xs-12 col-s-12 col-md-3 col-lg-3 col-xl-3">
      <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skill-interest.gif?alt=media&token=40c16eb3-524d-4312-b115-e420e9ef856c" alt="">
      <div class="card-body">
        <h5 class="card-title">Interests</h5>
      </div>
      Test
    </div>

    <div class="card col-xs-12 col-s-12 col-md-3 col-lg-3 col-xl-3">
      <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skills-trivia-game.gif?alt=media&token=79df161c-642b-4fe4-8386-22665e7aeb2a" alt="">
      <div class="card-body">
        <h5 class="card-title">Trivia</h5>
      </div>
      Test
    </div>

    <!-- <div class="col-md-1 col-lg-1 col-xl-1"></div> -->
  </div>
</template>

<script>

</script>

<style lang="scss">
  .aj-skills {
    width: 90%;
    margin-left: 7.5%
  }
  .card {
    margin: 25px;
    padding:0;
    max-width: 20%;
    // box-shadow: 4px 5px #666;
    -webkit-box-shadow: 0 8px 6px -6px black;
	   -moz-box-shadow: 0 8px 6px -6px black;
	        box-shadow: 0 8px 6px -6px black;
    img {
      height: 200px;
      width:100%;
    }
  }
  img.nyu-img {
    width: 30px;
    height: 30px;
  }

  .nyu {
    .nyu-header {
      font-size: 16px;
      font-weight: 700;
    }
    div {

    }
    .nyu-date {
      font-style: italic;
    }
  }
</style>
