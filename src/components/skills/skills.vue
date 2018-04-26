<template>
  <div class="aj-skills container-fluid">
    <!-- <div class="col-md-1 col-lg-1 col-xl-1"></div> -->
    <div class="row">
      <div class="card col col-12 col-sm-12 col-md-3 col-lg-3 col-xl-3">
        <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skills-study.gif?alt=media&token=4c36fef0-8ced-4ac0-a64a-e365f902ca4d" alt="">
        <div class="card-body">
          <h5 class="card-title">Academics</h5>
          <span class='nyu'>
            <img class='icon-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/nyu.jpg?alt=media&token=d393b56b-a48e-4cfc-8c4d-dee5bbc1a196">
            <span class='nyu-header'> New York University</span>
            <div> Tandon School of Engineering</div>
            <div> B.S. Computer Engineering, <span class='nyu-date'>2016</span></div>
            <div> B.S. Electrical Engineering, <span class='nyu-date'>2017</span></div>
          </span>
        </div>
      </div>

      <div class="card col col-12 col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-3">
        <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skill-programming.gif?alt=media&token=cb133233-e052-43a9-8e64-dd70807dec16" alt="">
        <div class="card-body">
          <h5 class="card-title">Programming</h5>
          <span class="skills-programming-section">
            <div>
              <img class="icon-img" src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/jsicon.png?alt=media&token=78b0e10e-8990-407c-b04d-6e49b59e6956">
              <span class="programming-text"> JavaScript, <span style="font-style:italic">5 years</span></span>
            </div>

            <div>
              <img class='icon-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/ruby.png?alt=media&token=13c4f7c2-af09-4b8d-bf83-54a01d561e11">
              <span class="programming-text"> Ruby, <span style="font-style:italic">3 years</span></span>
            </div>

            <div>
              <img class='icon-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/c%2B%2B.png?alt=media&token=55c96f8f-127c-4b9c-b5c9-93a848056b19">
              <span class="programming-text"> C++, <span style="font-style:italic">4 years</span></span>
            </div>

            <div>
              <img class='icon-img' src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/python.png?alt=media&token=78d002b7-2e01-43c2-bc90-fca3a6ae1f6e">
              <span class="programming-text"> Python, <span style="font-style:italic">4 years</span></span>
            </div>

          </span>
        </div>

      </div>

      <div class="card col col-12 col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-3">
        <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skill-interest.gif?alt=media&token=40c16eb3-524d-4312-b115-e420e9ef856c" alt="">
        <div class="card-body">
          <h5 class="card-title">Skill Set</h5>
          <ul class="skill-list">
            <li> Full Stack Web Development </li>
            <li> Microservices Engineering </li>
            <li> Test Driven Development</li>
            <li> Product Design </li>
            <li> Automation </li>
            <li> Building out Engineering, Design, and Product Teams</li>
            <li> Data Visualization</li>
          </ul>
        </div>
      </div>

      <div class="card col col-12 col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-3">
        <img src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/skills-trivia-game.gif?alt=media&token=79df161c-642b-4fe4-8386-22665e7aeb2a" alt="">
        <div class="card-body">
          <h5 class="card-title">Interests</h5>
          <span class="interests-list"></span>

          <div class="interest-list-item">
            <img class="icon-img" src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/leagueicon.jpeg?alt=media&token=d10e5e06-941e-4e02-b1a9-ed5ac941af73">
            <span><a href="http://na.op.gg/summoner/userName=the+fury">Competitive Gamer</a></span>
          </div>

          <div class="interest-list-item">
            <img class="icon-img" src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/fpgaicon.jpg?alt=media&token=5fe90c1d-08e6-4fe3-84a4-f492838c7f15">
            <span>FPGA Encryption</span>
          </div>

          <div class="interest-list-item">
            <img class="icon-img" src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/steakicon.jpg?alt=media&token=b1d30a0e-5b79-41e7-b781-10dd300f6cf8">
            <span>Trying to Cook the Perfect Steak</span>
          </div>

          <div class="interest-list-item">
            <img class="icon-img" src="https://firebasestorage.googleapis.com/v0/b/abeyjoysite.appspot.com/o/scootericon.jpg?alt=media&token=0ac69b13-24f7-4443-a01e-329179ae93ef">
            <span>Exploring the West Coast</span>
          </div>
        </div>
      </div>
    </div>


    <!-- <div class="col-md-1 col-lg-1 col-xl-1"></div> -->
  </div>
</template>

<script>

</script>

<style lang="scss">
  .aj-skills {

  }
  .card {
    // margin: 1%;
    padding: 0;
    -webkit-box-shadow: 0 8px 6px -6px black;
	   -moz-box-shadow: 0 8px 6px -6px black;
	        box-shadow: 0 8px 6px -6px black;
    img {
      height: 200px;
      width:100%;
    }
  }
  img.icon-img {
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

  .skill-list {
    padding: 0 15px;
  }

  .interest-list-item {
    padding: 10px 0;
  }
</style>
