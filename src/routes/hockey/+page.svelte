<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Hockey</h1>
  <div class="columns">
    <!-- start of tile -->
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-11">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/hockey.png" alt="hockey" />
            </article>
            <article class="tile is-child">
              <Image src="/hockey3.png" alt="hockey" />
            </article>
            <article class="tile is-child">
              <Image src="/hockey2.png" alt="hockey" />
            </article>
          </div>
          <!-- end of tile -->
          <div class="column" />
          <!-- start of second column -->
          <div class="column is-4">
            <h3>Chairperson: Andrew Smith</h3>
            <br />
            <h2>LEVELS</h2>
            <p>Years 7-13</p>
            <br />
            <h2>TERMS</h2>
            <p>Terms 2 and 3</p>
            <br />
            <h2>​​​​​​​Information</h2>
            <p>
              For all new Hockey Parents you are invited to join the “Craighead Hockey” facebook page where all hockey information will be posted.
              <br />
              We have the new Hockey South Canterbury affiliation and practise fees which have been increased this year.
            </p>
            <br />
            <h3>​​​​​​​Subs TBC for 2023.</h3>
            <ul>
              <li>2023 Subs for 1st XI Team - $</li>
              <li>2023 Subs for 2nd XI Team - $</li>
              <li>2023 Subs for Junior Teams -</li>
            </ul>
            <p>All subs will be charged to your account</p>
            <br />
            <h2>FACEBOOK</h2>
            <p>There has been a Facebook page set up for Craighead Hockey, for players, parents, caregivers and coaches. This will be a way of getting quick messages out to the girls and parents.</p>
            <h2>UNIFORM</h2>
            <ul>
              <li>A Team - Dress supplied. Socks to be purchased.</li>
              <li>Other teams - Top supplied. Skirt and socks to be purchased</li>
              <li>Primary teams are supplied with a top. Skirt and socks to be purchased.All girls are to wear school tracksuit to and from game</li>
            </ul>
            <br />
            <p>
              Hockey will be played at the Hockey Turf, beside the Comunity Trust Sports Centre on Morgans Rd. Senior A on Saturdays and Senior B/C on Sundays. The draw is published on the Hockey South Canterbury Website.
              <br />
            </p>
            <p>Click on the button below</p>
            <br />
            <!-- start button -->
            <div class="buttons">
              <a class="button is-info is-light is-large is-hovered" href="https://www.sporty.co.nz/hockeysouthcanterbury">Hockey South Canterbury</a>
            </div>
            <!-- end of button -->
            <br />
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
</style>
