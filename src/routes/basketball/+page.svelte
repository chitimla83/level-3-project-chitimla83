<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Basketball</h1>
  <div class="columns">
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-11">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/basketball.png" alt="school athletics" />
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
                <div class="tile is-child is-6">
                  <Image src="/placeholder.png" alt="Sasha Smilie" />
                </div>
                <!-- child -->
                <div class="tile is-child">
                  <h3>Teacher in Charge - Sasha Smilie</h3>
                  <p>smilliesa@craighead.school.nz</p>
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
            <h2>2023 COSTS TBC</h2>
            <br />
            <h2>UNIFORM</h2>
            <p>School shorts, singlet provided, court shoes. Senior A - uniform supplied</p>
            <br />
            <h2>Team Supervision:</h2>
            <p>Each team <strong>MUST</strong> have adult supervision while they are at the venue, while their team is either playing or carrying out their duty. (If the venue controller requests to speak to a team's supervisor and the players cannot bring this person to the controller, the team will be penalised).</p>
            <br />
            <h2>Reschedules and Defaults:</h2>
            <p>SCBA of any intending dates their teams are not available to play, <strong>no less than the Friday previous to that date. </strong></p>
          </div>
        </div>

        <h2>DUTY ON A FRIDAY NIGHT INVOLVES;</h2>
        <ul>
          <li>1.Three on Bench Duty (keeping score, etc)</li>
          <li>2. One on Referee Duty (must have own whistle)</li>
        </ul>

        <p><strong>REMEMBER; all teams MUST have an adult on their bench while they are playing their game</strong></p>
        <ul>
          <li>No bench -$50 fine</li>
          <li>No competent referee - $50</li>
          <li>No adult present - $50</li>
        </ul>

        <br />
        <h2>Coaching and Duty Clinics:</h2>
        <p>
          SCBA will be holding <strong> Referees clinic on and a Score Bench Course on </strong>at the STEC (Aorangi Stadium) Morgans Road.
          <br />
          <strong>EACH CRAIGHEAD TEAM MUST HAVE 3/4 PLAYERS ATTEND THESE CLINICS </strong>
        </p>
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
