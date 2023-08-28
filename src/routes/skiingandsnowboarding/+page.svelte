<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>SKIING/SNOWBOARDING</h1>
  <div class="columns">
    <!-- start of tile -->
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-12">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/skiing.png" alt="skiing" />
            </article>
            <article class="tile is-child">
              <Image src="/skiing2.png" alt="skiing" />
            </article>
            <article class="tile is-child">
              <Image src="/skiing3.png" alt="skiing" />
            </article>
          </div>
          <!-- end of tile -->
          <div class="column" />
          <!-- start of second column -->
          <div class="column">
            <!-- start of tile s -->
            <div class="tile is-ancestor">
              <div class="tile is-parent">
                <div class="tile is-child is-4">
                  <Image src="/devyngilbert.JPG" alt="Devyn Gilbert" />
                </div>
                <!-- child -->
                <div class="tile is-child">
                  <h2>Teacher in Charge - Devy Gilbert</h2>
                  <p>gilbertde@craighead.school.nz</p>
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
          </div>
        </div>
        <h2>Aoraki Skiing/Snowboarding 2022</h2>
        <p>On Monday 15 August approx 30 girls competed in the Aoraki Skiing competititon at Mt Dobson.</p>
        <br />
        <h3>Slalom:</h3>
        <li>Neve Ball - 1st in Year 7&8 girls</li>
        <li>Greta Murray - 2nd in Year 9/10 girls</li>
        <li>Lucy Zuppicich - 3rd in Year 9&10 girls</li>
        <li>Elsie Talbot - 3rd in Year 11-13 girls</li>
        <br />
        <h3>Snowboard/Time Trial</h3>
        <li>Emily Coleman - 2nd in Snowboard Time Trial and 1st in the Boardercross</li>
        <br />
        <br />
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
</style>
