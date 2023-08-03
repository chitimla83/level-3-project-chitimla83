<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Rugby</h1>

  <div class="columns">
    <!-- start of tile -->
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-12">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/rugby.png" alt="rugby" />
            </article>
            <article class="tile is-child">
              <Image src="/rugby2.png" alt="rugby" />
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
                  <Image src="/Mason M.JPG" alt="Max Mason" />
                </div>
                <!-- child -->
                <div class="tile is-child">
                  <h2>Teacher in Charge - Max Mason</h2>
                  <p>masonma@craighead.school.nz</p>
                </div>
                <!-- child -->
              </div>
              <!-- parent  -->
            </div>
            <!-- ancestor -->
            <!-- end of new tile -->

            <p>
              ​The Mid-South Canterbury Schoolgirls Rugby is played at various school grounds on Wednesday afternoons, with start times normally about 4.15pm.
              <br />
              Years - 9-13
            </p>
            <h3>The 2023 Rugby season.</h3>
            <p>
              Teams for the 2022 Rugby Season are:
              <br />
              U18, U15, U15 Development and U13.
              <br />
              U13 Coaches are
              <br />
              U15 Coaches are
              <br />
              U15 Development Coaches are
              <br />
              1st XV Coaches are Mick Geary and
            </p>
            <li>Team training will be on Monday 3.30 – 5.00pm and also on a Wednesday (same time) when there isn’t a game scheduled.</li>
            <li>Training: With the School grounds not able to be used, training will be at Alpine Energy.</li>
            <li>The teacher-in-charge / manager is TBC who will be responsible for all non-coaching aspects for the season.</li>
            <li>The competition format is a round-robin one with games being played on a Wednesday afternoon.</li>

            <p>Home games will be played at Alpine Energy Stadium. Start times will depend on whether or not the opposition has to travel, but will be between 4.15 pm and 5.00pm.</p>
            <br />
            <p>Away games: at times during the season we will need to travel for ‘away’ games. As these games need to start at 4.30 this will mean that we would need to leave school at the end of period 4 on a Wednesday.</p>
            <br />
            <p>The team will be notified each Monday of the exact game time for that week.</p>
            <br />
            <h2>UNIFORM</h2>
            <p>School shorts, rugby jersey (issued), green socks, boots and mouthguard</p>
            <br />
            <p>Please note that for all games girls will need: - School shorts, school rugby jersey, school socks, warm-up tracksuit pants and top, mouthguard (no mouthguard = no play!), own strapping tape.</p>
            <br />
            <h2>The fees for the 2023 season are: TBC</h2>
            <p>
              <strong
                >All subs will be charged to your account.
                <br />
                ​​​​​​​HOWEVER: WE ALSO NEED 1 OR 2 PARENTS TO ASSIST WITH MANAGING THE TEAM AND ALSO WITH FIRST AID – IF YOU CAN HELP IN THIS REGARD PLEASE CONTACT MR MULLHOLLAND.
              </strong>
              <br />
              If you have any queries or would like to discuss any aspect of the rugby season or team, then please don’t hesitate to contact Mr Mulholland.
            </p>
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
