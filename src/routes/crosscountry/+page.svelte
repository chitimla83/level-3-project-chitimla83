<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Cross Country</h1>

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
  <h2>LEVELS</h2>
  <p>Years 7-13</p>
  <br />
  <h2>Terms 2 and 3</h2>
  <h2>COST TBD</h2>
  <br />
  <h2>IMPORTANT DATES 2023</h2>
  <p>School Cross Country - April 6</p>
  <p>Aoraki Cross Country - Tuesday 16 May, Ashbury Park, Timaru</p>
  <br />
  <h2>UNIFORM</h2>
  <p>Sports PE Top and Shorts, white socks and gymshoes</p>
  <br />
  <p>Craighead has a proud history of success and participation in athletics and developed a strong sense of 'team' in what is often perceived as an individual sport. Craighead is committed to facilitating opportunities for students to compete at a regional, South Island and national level in both athletics and cross country on an annual basis. Craighead is focused on developing talent and participation working closely with the South Canterbury Amateur Athletics Club to provide coaching opportunities for those that wish to understand more about the different disciplines. Trainings are on Mondays from 4pm at the Stadium and begin in early September.</p>
  <br />
  <br />

  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="crosscountryresults">Cross Country Results</a>
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
  .is-child {
    display: flex !important;
    align-items: center !important;
  }
</style>
