<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Athletics</h1>
  <br />

  <!-- teachcer in charge image in tile  -->
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

  <!-- information that was on the right colummun -->
  <h2>​LEVELS</h2>
  <p>Years 7-13</p>
  <br />
  <h2>TERMS</h2>
  <p>Terms 1 and 4</p>
  <br />
  <h2>IMPORTANT DATES 2023</h2>
  <ul>
    <li>Aoraki Athletics - Wednesday 16 March, Ashburton</li>
    <li>South Island Athletics - 1-3 April, Christchurch</li>
    <li>National Athletics - December</li>
  </ul>

  <br />
  <h2>UNIFORM</h2>
  <ul>
    <li>PE or House coloured t-shirt/green shorts - Sports Days</li>
    <li>CDS Athletics Singlet/Shorts, CDS Rugby Jersey/Merino/Jacket/House Top</li>
  </ul>

  <br />
  <p>Craighead has a proud history of success and participation in athletics and developed a strong sense of 'team' in what is often perceived as an individual sport. Craighead is committed to facilitating opportunities for students to compete at a regional, South Island and national level in both athletics and cross country on an annual basis.</p>
  <br />
  <p>Craighead is focused on developing talent and participation working closely with the South Canterbury Amateur Athletics Club to provide coaching opportunities for those that wish to understand more about the different disciplines. Trainings are on Mondays from 4pm at the Stadium and begin in early September.</p>

  <br />
  <br />

  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="athleticsresults">Athletics Results</a>
  </div>
  <!-- end of button -->
  <br />

  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-4">
        <Image src="/athletics.png" alt="School Athletics" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <Image src="/athletics2.png" alt="School Athletics" />
      </div>
      <!-- child -->
    </div>
    <!-- parent  -->
  </div>
  <!-- ancestor -->
  <!-- end of new tile -->
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
    max-width: 35%;
  }
</style>
