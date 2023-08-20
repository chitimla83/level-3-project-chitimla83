<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Cricket</h1>
  <div class="columns">
    <!-- start of tile -->
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-11">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/cricket.png" alt="Craighead girl playing cricket externally" />
            </article>
          </div>
          <!-- end of tile -->

          <div class="column" />
          <!-- start of second column -->
          <div class="column">
            <!-- start of tile s -->
            <div class="tile is-ancestor">
              <div class="tile is-parent">
                <div class="tile is-child is-6">
                  <Image src="/jmuholland.png" alt="Jacob Muholland" />
                </div>
                <!-- child -->
                <div class="tile is-child">
                  <h3>Teacher in Charge - Mr Muholland</h3>
                  <p>mulhollandja@craighead.school.nz</p>
                </div>
                <!-- child -->
              </div>
              <!-- parent  -->
            </div>
            <!-- ancestor -->
            <!-- end of new tile -->

            <h2>LEVELS</h2>
            <p>Years 7-13</p>
            <br />
            <h2>TERMS</h2>
            <p>Terms 1</p>
            <br />
            <h2>UNIFORM</h2>
            <p>School Shorts, sleeved PE top,</p>
            <br />
          </div>
        </div>

        <h2>Women's Quick Smash Cricket</h2>
        <ul>
          <li>All games are being played on a Monday night at Ashbury Park</li>
          <li>Runs for 6 consecutive Monday evenings</li>
          <li>8 females per side</li>
          <li>12 overs per side</li>
          <li>Wides and no balls worth 1 run each</li>
          <li>Batters bat in pairs</li>
          <li>Each batting pair bats for 3 overs</li>
          <li>Loss of a wicket means 6 runs taken off score</li>
          <li>Each player has to bowl at least 1 over</li>
          <li>Incrediball used, no need for pads or helmets</li>
          <li>Plastic stumps or wooden springback stumps to be used</li>
          <li>No cost to enter</li>
        </ul>
        <br />
      </div>
    </div>
  </div>
</main>

<style>
  h1 {
    font-family: "Poppins";
    font-size: 40px;
    text-align: center;
    color: #236093;
    font-weight: bolder;
  }
  h2 {
    font-family: "Poppins";
    font-size: 25px;
    padding-left: 45px;
  }
  p {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    padding-right: 60px;
    padding-left: 60px;
  }
  li {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 70px;
    list-style-type: circle;
    margin-right: 20px;
  }
  h3 {
    font-family: "Poppins";
    font-size: 20px;
    margin-left: 50px;
    margin-right: 20px;
  }
</style>
