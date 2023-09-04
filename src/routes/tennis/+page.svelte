<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Tennis</h1>
  <br />
  <!-- start of tile s -->
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-3">
        <Image src="/dianesurridge.png" alt="Diane Surridge" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <h3>
          Teacher in Charge - Diane Surridge
          <br />
          surridgedi@craighead.school.nz
        </h3>
      </div>
      <!-- child -->
    </div>
    <!-- parent  -->
  </div>
  <!-- ancestor -->
  <!-- end of new tile -->

  <p>The Secondary Schools Tennis Competition (Years 9-13) is played at the Trust Aoraki Tennis Centre on a Wednesday afternoon, starting at 4.15pm .(gates open at 4pm), Round one will start approximately at 4.15pm (30 minutes) and Round 2 at 5.00pm. (TO BE CONFIRMED)</p>
  <br />
  <h2>LEVELS:</h2>
  <p>Years 7- 13</p>
  <br />
  <h2>TERM:</h2>
  <p>1</p>
  <br />
  <h2>COST</h2>
  <p>TBD</p>
  <br />
  <h2>IMPORTANT DATES 2023</h2>
  <p>Aoraki Tennis - Thursday 16 February, Timaru</p>
  <br />
  <h2>Aoraki Tennis - Thursday 16 February, Timaru</h2>
  <br />
  <br />
  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="tennisresults">Tennis Results</a>
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
  .is-child {
    display: flex !important;
    align-items: center !important;
  }
  div {
    margin-left: 40px;
  }
</style>
