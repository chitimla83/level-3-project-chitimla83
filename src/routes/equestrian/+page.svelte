<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Equestrian</h1>

  <!-- start of tile s -->
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-3">
        <Image src="/placeholder.png" alt="Katie Mackenzie" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <h3>
          Teacher in Charge - Katie Mackenzie
          <br />
          mackenzieka@craighead.school.nz
        </h3>
      </div>
      <!-- child -->
    </div>
    <!-- parent  -->
  </div>
  <!-- ancestor -->
  <!-- end of new tile -->

  <h2>LEVELS</h2>
  <p>Year 7-13</p>
  <br />
  <h2>TERMS</h2>
  <p>Terms 2 and 3</p>
  <br />
  <h2>COST TBD</h2>
  <br />

  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="equestrianresults">Equestrian Results</a>
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

  h3 {
    font-family: "Poppins";
    font-size: 20px;
    margin-left: 50px;
    margin-right: 20px;
  }
  div {
    margin-left: 40px;
  }
  .is-child {
    display: flex !important;
    align-items: center !important;
  }
</style>
