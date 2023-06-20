<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Nav />
<Header title="Craighead Diocesan School" subtitle="Sports Portal" />
<main>
  <h1>Basketball</h1>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <h2>LEVELS</h2>
      <p>Years 7-13</p>
      <h2>TERMS</h2>
      <p>Terms 2 and 3</p>
      <h2>Teacher in Charge - Mr Mulholland and Ms Smillie</h2>
      <p>Aoraki JuniorBasketball - Wednesday 22 June, Timaru</p>
      <h2>2023 COSTS TBC</h2>
      <h2>UNIFORM</h2>
      <p>School shorts, singlet provided, court shoes. Senior A - uniform supplied</p>
      <h2>Teacher in Charge - Ms Smillie</h2>

      <h2>Team Supervision:</h2>
      <p>Each team <strong>MUST</strong> have adult supervision while they are at the venue, while their team is either playing or carrying out their duty. (If the venue controller requests to speak to a team's supervisor and the players cannot bring this person to the controller, the team will be penalised).</p>
      <h2>Reschedules and Defaults:</h2>
      <p>SCBA of any intending dates their teams are not available to play, <strong>no less than the Friday previous to that date. </strong></p>
      <h2>Coaching and Duty Clinics:</h2>
      <p>
        SCBA will be holding <strong> Referees clinic on and a Score Bench Course on </strong>at the STEC (Aorangi Stadium) Morgans Road.
        <br />
        <strong>EACH CRAIGHEAD TEAM MUST HAVE 3/4 PLAYERS ATTEND THESE CLINICS </strong>
      </p>
      <!-- put infor in here  -->
    </div>
  </div>

  <h2>DUTY ON A FRIDAY NIGHT INVOLVES;</h2>
  <li>1.Three on Bench Duty (keeping score, etc)</li>
  <li>2. One on Referee Duty (must have own whistle)</li>
  <p><strong>REMEMBER; all teams MUST have an adult on their bench while they are playing their game</strong></p>
  <li>No bench -$50 fine</li>
  <li>No competent referee - $50</li>
  <li>No adult present - $50</li>
</main>
<Footer />

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
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
  }
  h3 {
    font-family: "Poppins";
    font-size: 20px;
  }
</style>
