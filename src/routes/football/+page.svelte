<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Football</h1>
  <div class="columns">
    <!-- start of tile -->
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-12">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/footbakll.png" alt="football" />
            </article>
            <article class="tile is-child">
              <Image src="/football2.png" alt="football" />
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
                  <Image src="/Townshend.JPG" alt="Alastair Townshend" />
                </div>
                <!-- child -->
                <div class="tile is-child">
                  <h2>Teacher in Charge - Alastair Townshend</h2>
                  <p>townshendal@craighead.school.nz</p>
                </div>
                <!-- child -->
              </div>
              <!-- parent  -->
            </div>
            <!-- ancestor -->
            <!-- end of new tile -->

            <h2>LEVELS</h2>
            <p>Years 9-13</p>
            <br />
            <h2>TERMS</h2>
            <p>Terms 2 and 3</p>
            <br />
            <p>
              <strong>
                Competition starts Term 2
                <br />
                Games start at 4pm at different football fields around Timaru on a Thursday.</strong
              >
            </p>
            <br />
            <h2>UNIFORM</h2>
            <p>Uniform supplied. Boots.</p>
            <br />
            <p>Football is played on a Thursday afternoon at various football grounds in Timaru. The A team comp</p>
          </div>
        </div>
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
  }
  p {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
  }
  li {
    list-style-type: circle;
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 50px;
  }
  h3 {
    font-family: "Poppins";
    font-size: 20px;
  }
</style>
