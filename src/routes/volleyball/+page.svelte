<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Volleyball</h1>
  <br />
  <!-- start of tile s -->
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-3">
        <Image src="/andrewjones.JPG" alt="placeholder" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <h3>
          Teacher in Charge - Andrew Jones
          <br />
          jonesan@craighead.school.nz
        </h3>
      </div>
      <!-- child -->
    </div>
    <!-- parent  -->
  </div>
  <!-- ancestor -->
  <!-- end of new tile -->

  <p>Volleyball is played on a Friday evening at the SBS Events Centre, Morgans Rd. Competition will be starting with games from 6.00pm to 8.00pm. Although teams have dedicated student coaches, we require at least one parent from each team to supervise games. A roster will be organised at the beginning of the season. It is also essential that your daughter does duty on the evenings that this is required. Without teams completing this we would not have a competition. Any teams that do not undertake their Duty requirements will be deducted competition points plus fined $50. Thank you in advance for this.</p>
  <br />
  <h2>LEVELS</h2>
  <p>Years 9-13</p>
  <br />
  <h2>TERMS</h2>
  <p>Terms 1 and 4</p>
  <br />
  <h2>IMPORTANT DATES</h2>
  <p>Aoraki Volleyball - Thursday 23 March, Timaru</p>
  <br />
  <h2>UNIFORM</h2>
  <p>PE shorts, top provided, white socks, gymshoes</p>
  <br />
  <br />
  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="volleyballresults">Volleyball Results</a>
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
