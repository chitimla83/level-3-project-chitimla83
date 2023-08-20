<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Table Tennis</h1>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <div class="column">
        <!-- start of tile s -->
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <div class="tile is-child is-4">
              <Image src="/dianesurridge.png" alt="Diane Surridge" />
            </div>
            <!-- child -->
            <div class="tile is-child">
              <h3>Teacher in Charge - Diane Surridge</h3>
              <p>surridgedi@craighead.school.nz</p>
            </div>
            <!-- child -->
          </div>
          <!-- parent  -->
        </div>
        <!-- ancestor -->
        <!-- end of new tile -->
        <p>Table Tennis is played on a Wednesday night at the Barry Butler Table Tennis Stadium on Coonoor Rd, 56.30pm to 78.00pm.</p>
        <br />
        <h2>LEVELS</h2>
        <p>Years 9-13</p>
        <br />
        <h2>TERMS</h2>
        <p>Terms 2 and 3</p>
        <br />
        <h2>COST</h2>
        <p>$15 Monday Night Competition ($45 Team of 3)</p>
        <br />
        <h2>IMPORTANT DATES 2023</h2>
        <p>Friday 18 August - Aoraki Table Tennis</p>
        <br />
        <h2>UNIFORM</h2>
        <p>School PE Uniform</p>
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
