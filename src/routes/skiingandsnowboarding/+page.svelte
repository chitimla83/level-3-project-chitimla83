<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>SKIING/SNOWBOARDING</h1>
  <br />
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-3">
        <Image src="/devyngilbert.JPG" alt="Devyn Gilbert" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <h3>
          Teacher in Charge - Devy Gilbert
          <br />
          gilbertde@craighead.school.nz
        </h3>
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
  <p>Terms 2 and 3</p>
  <br />
  <h2>COST</h2>
  <p>TBD</p>
  <br />
  <h2>IMPORTANT DATES 2023</h2>
  <p>Aoraki Snow Sports - Monday 14 August, Mt Dobson</p>
  <br />
  <h2>UNIFORM</h2>
  <p>Own appropriate Gear, Safety Gear</p>
  <br />
  <br />
  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="skiingandsnowboardingresults">Skiing and Snowboarding Results</a>
  </div>
  <!-- end of button -->
  <br />
  <br />
  <br />
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
    margin-left: 50px;
  }
  p {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 50px;
    margin-right: 20px;
  }
  li {
    list-style-type: circle;
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 50px;
    margin-right: 20px;
  }
  h3 {
    font-family: "Poppins";
    font-size: 20px;
    margin-left: 50px;
  }
  .is-child {
    display: flex !important;
    align-items: center !important;
  }
  div {
    margin-left: 40px;
  }
</style>
