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
        <span class="skills-programming-section">
          <div>
            <img class="prg-img" src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/jsicon.png?alt=media&token=78b0e10e-8990-407c-b04d-6e49b59e6956">
            <span class="programming-text"> JavaScript, <span style="font-style:italic">5 years</span></span>
          </div>

          <div>
            <img class='prg-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/ruby.png?alt=media&token=13c4f7c2-af09-4b8d-bf83-54a01d561e11">
            <span class="programming-text"> Ruby, <span style="font-style:italic">3 years</span></span>
          </div>

          <div>
            <img class='prg-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/c%2B%2B.png?alt=media&token=55c96f8f-127c-4b9c-b5c9-93a848056b19">
            <span class="programming-text"> C++, <span style="font-style:italic">4 years</span></span>
          </div>

          <div>
            <img class='prg-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/python.png?alt=media&token=78d002b7-2e01-43c2-bc90-fca3a6ae1f6e">
            <span class="programming-text"> Python, <span style="font-style:italic">4 years</span></span>
          </div>

        </span>
      </div>

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
  img.nyu-img, img.prg-img {
    width: 30px;
    height: 30px;
  }

  .nyu {
    .nyu-header {
      font-size: 16px;
      font-weight: 700;
    }
    .nyu-date {
      font-style: italic;
    }
  }

  .skills-programming-section {
    div {
      margin: 10px 0px;
    }
    .programming-text {
      vertical-align: -webkit-baseline-middle;
    }
  }

</style>
