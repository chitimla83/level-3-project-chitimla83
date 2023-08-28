<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Bandminton</h1>
  <!-- start of tile s -->
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-6">
        <Image src="/dylangibbs.jpg" alt="Dylan Gibbs" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <h3>
          Teacher in Charge-
          <br />
          Dylan Gibbs
        </h3>
        <br />
        <p>gibbsdy@craighead.school.nz</p>
      </div>
      <!-- child -->
    </div>
    <!-- parent  -->
  </div>
  <!-- ancestor -->
  <!-- end of new tile -->

  <h2>​YEARS</h2>
  <p>Years 9-13</p>
  <br />
  <h2>​TERMS</h2>
  <p>​ Terms 1 and 2</p>
  <br />
  <h2>COST - approx $45</h2>
  <br />
  <h2>IMPORTANT DATES 2023</h2>
  <ul>
    <li>Weekly Competition starts - Start of Term 2</li>
    <li>Aoraki Badminton - Tuesday 3 August</li>
  </ul>
  <br />
  <h2>UNIFORM</h2>
  <p>School sports uniform, gymshoes</p>
  <br />
  <p>Badminton is played on a Tuesday night at the SBS Events Centre, Morgans Rd. Competition is for 10 weeks and starts on the TBC and conclude at the end of Term 2. Juniors start at 6.15pm and Seniors at 7.35pm.</p>

  <br />
  <br />
  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="badmintonresults">Badminton Results</a>
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
  div {
    margin-left: 40px;
  }
</style>
