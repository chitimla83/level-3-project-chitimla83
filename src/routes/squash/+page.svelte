<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Squash</h1>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <!-- start of tile s -->
      <div class="tile is-ancestor">
        <div class="tile is-parent">
          <div class="tile is-child is-4">
            <Image src="/dianesurridge.png" alt="Diane Surridge" />
          </div>
          <!-- child -->
          <div class="tile is-child">
            <h2>Teacher in Charge - Diane Surridge</h2>
            <p>surridgedi@craighead.school.nz</p>
          </div>
          <!-- child -->
        </div>
        <!-- parent  -->
      </div>
      <!-- ancestor -->
      <!-- end of new tile -->
      <h2>LEVELS</h2>
      <p>Years 9-13</p>
      <br />
      <h2>TERMS</h2>
      <p>Terms 2 and 3</p>
      <br />
      <h2>COST</h2>
      <p>TBD</p>
      <br />
      <h2>IMPORTANT DATES 2023</h2>
      <p>Aoraki Squash - Wednesday 7 June</p>
      <br />
      <h2>UNIFORM</h2>
      <p>School PE Uniform</p>
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
  }
  p {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    margin-left: 20px;
    margin-right: 20px;
  }
  li {
    list-style-type: circle;
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 20px;
    margin-right: 20px;
  }
  h3 {
    font-family: "Poppins";
    font-size: 20px;
  }
</style>
