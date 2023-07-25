<script>
  import Image from "$lib/Image.svelte"
</script>

<h1>Netball</h1>
<main>
  <div class="columns">
    <!-- put images -->

    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <!-- start of tile s -->
      <div class="tile is-ancestor">
        <div class="tile is-parent">
          <div class="tile is-child is-4">
            <Image src="/ellashaw.JPG" alt="placeholder" />
          </div>
          <!-- child -->
          <div class="tile is-child">
            <h2>Teacher in Charge - Ella Shaw</h2>
            <p>shawel@craighead.school.nz</p>
          </div>
          <!-- child -->
        </div>
        <!-- parent  -->
      </div>
      <!-- ancestor -->
      <!-- end of new tile -->

      <p>
        Netball is played on a Saturday at the Aorangi Courts on Morgans Road.
        <br />
        Juniors (years 7&8) in the morning
        <br />
        Seniors (years 9-13) in the afternoon
        <br />
        Premier Grade teams (Senior A and Senior B) play on a Wednesday night in the STEC Stadium.
        <br />
        Trials for all Netball teams will be in the first term. Details will be given to students at school in the notices and newsletter.
      </p>
      <br />
      <h2>LEVELS</h2>
      <p>Years 7-13</p>
      <br />
      <h2>TERMS</h2>
      <p>Terms 2 and 3</p>
      <br />
      <h2>NETBALL SUBS 2023 TBC</h2>
      <p>
        Junior (Years 7 & 8) $ Years 9/10/Senior Reserve $
        <br />
        Senior A Team $
        <br />
        Senior B Team $
        <br />
        All subs will be charged to your account.
      </p>
      <br />
      <h2>​​​​IMPORTANT DATES FOR 2023</h2>
      <p>​Rangi Ruru Exchange - Thursday 22 June</p>
      <br />
      <h2>UNIFORM</h2>
      <br />
      <p>
        Senior A, B and Senior Reserve - netball dresses
        <br />
        All other teams wear the new netball uniform, skirt and top.
        <br />
        All teams to wear white socks and gymshoes.
      </p>
      <br />

      <h2>Click on the buttons to access the following:</h2>
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="https://www.netballsouthcanterbury.co.nz/">Weekly Draws and Results</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="https://forms.gle/3K741D6jbPW3NCMMA">Netball Sign Ups 2023</a>
      </div>
      <!-- end of button -->
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
    margin-left: 20px;
    margin-right: 20px;
  }
  li {
    list-style-type: circle;
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 20px;
    margin-right: 20px;
  }
  h3 {
    font-family: "Poppins";
    font-size: 20px;
  }
</style>
