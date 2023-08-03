<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Swimming</h1>
  <div class="columns">
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-11">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/swimming.png" alt="school athletics" />
            </article>
            <article class="tile is-child">
              <Image src="/basketball3.png" alt="school athletics" />
            </article>
          </div>

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
            <p>Years 7-13</p>
            <br />
            <h2>TERMS</h2>
            <p>Terms 1 and 4</p>
            <br />
            <h2>COST</h2>
            <p>Aorakis - $3 per event</p>
            <br />
            <h2>IMPORTANT DATES 2023</h2>
            <p>Aoraki Swimming - Friday 26 May, Ashburton</p>
          </div>
        </div>

        <h2>2023 Swimming Sports</h2>
        <h3>Inter-House Relay</h3>
        <ul>
          <li>1st Te Rawhiti (Rec)</li>
          <li>2nd Te Uru</li>
          <li>3rd Te Tonga</li>
          <li>1st Te Rawhiti (Rec)</li>
          <li>2nd Te Uru</li>
          <li>3rd Te Tonga</li>
          <br />
          <h3>Boarders vs Daygirls Relay</h3>
          <li>1st Day Girls</li>
          <li>2nd Boarders</li>
          <br />
        </ul>
        <h3>Long Plunge</h3>
        <ul>
          <li>1st Te Rawhiti</li>
          <li>2nd Te Uru</li>
          <li>3rd Te Raki</li>
          <br />
        </ul>

        <h3>Miss B Howell Cup Champion House</h3>
        <ul>
          <li>1st Te Rawhiti</li>
          <li>2nd Te Uru</li>
          <li>3rd Te Tonga</li>
          <br />
        </ul>

        <h3>Grade Champions and Runner Ups:</h3>
        <ul>
          <li>Minor Champion: Francesca Gough</li>
          <li>Runner up: Martina Naydenova</li>
          <br />
          <li>Junior Champion: Megan Scott</li>
          <li>Runner up:Olivia Walsh</li>
          <br />
          <li>Dr C S Fraser Cup Intermediate Champion:Victoria Kyle</li>
          <li>Runner Up: Dimana Naydenova</li>
          <br />
          <li>Senior Champion: Amalia Cabrera-Martin</li>
          <li>Runner up: Briar Annett</li>
        </ul>
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
    margin-left: 25px;
  }
  p {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 20px;
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
    margin-left: 25px;
  }
  ul {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
  }
</style>
