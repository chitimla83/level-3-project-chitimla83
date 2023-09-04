<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Touch</h1>
  <br />
  <!-- start of tile s -->
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-3">
        <Image src="/jmuholland.png" alt="Jacob Mulholland" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <h3>
          Teacher in Charge - Jacob Mulholland
          <br />
          mulhollandja@craighead.school.nz
        </h3>
      </div>
      <!-- child -->
    </div>
    <!-- parent  -->
  </div>
  <!-- ancestor -->
  <!-- end of new tile -->

  <p>Touch is played on a Thursday night at the Old Boys Lower Grounds.</p>
  <br />
  <h2>Grades Are:</h2>
  <ul>
    <li>Junior (Years 7&8): 4.00pm and 4.45pm</li>
    <li>Secondary: 5.15pm and 5.50pm</li>
    <li>Womens A & B (Competitive) & Social:6.00pm to 8.00pm (depending on the draw)</li>
  </ul>
  <br />
  <h2>IMPORTANT DATES 2023</h2>
  <p>Aoraki Touch - Sunday 5 March, Timaru</p>
  <br />

  <h3><strong> Parent Manager: ALL TEAMS MUST HAVE A PARENT AT ALL OF THEIR GAMES </strong></h3>
  <br />
  <h2>COST</h2>
  <p>TBD</p>
  <br />
  <h2>UNIFORM</h2>
  <p>
    Senior A/B - PE shorts, top issued
    <br />
    Junior A - PE shorts, top issued
    <br />
    Social teams - own uniform, same coloured tops
  </p>
  <br />
  <h2>DRAW</h2>
  <p>A draw will be made prior to Round 1 and again prior to Round 2. The draw can be viewed at on the button below and also on the school sports portal website. Any postponements will be on the website.</p>
  <br />

  <h2>REFEREES</h2>
  <p>Primary and Secondary teams MUST supply a referee for the game they are playing in. Women's teams MUST supply a referee for the game prior to or following their own game. (Note: training sessions for prospective referees will be organised at School and all teams must have their referees attend).</p>
  <br />
  <br />
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="https://www.timaruoldboys.com/">Touch Draw</a>
    <a class="button is-info is-light is-large is-hovered" href="touchresults">Touch Results</a>
  </div>
  <!-- end of button -->
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
