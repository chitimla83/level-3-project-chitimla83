<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Nav />
<Header title="Craighead Diocesan School" subtitle="Sports Portal" />
<main>
  <h1>Bandminton</h1>

  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <h2>​YEARS</h2>
      <p>Years 9-13</p>
      <br />
      <h2>​TERMS</h2>
      <p>​ Terms 1 and 2</p>
      <br />
      <h2>COST - approx $45</h2>
      <br />
      <h2>IMPORTANT DATES 2023</h2>
      <li>Weekly Competition starts - Start of Term 2</li>
      <li>Aoraki Badminton - Tuesday 3 August</li>
      <br />
      <h2>UNIFORM</h2>
      <p>School sports uniform, gymshoes</p>
      <br />
      <h2>Teacher in Charge - Mr Gibbs</h2>
      <br />
      <p>Badminton is played on a Tuesday night at the SBS Events Centre, Morgans Rd. Competition is for 10 weeks and starts on the TBC and conclude at the end of Term 2. Juniors start at 6.15pm and Seniors at 7.35pm.</p>
    </div>
  </div>
  <!-- end of column  -->
  <!-- no column  -->
  <p>This Tuesday saw the end of the 2022 Timaru Secondary Schools Badminton Competition. This year has been another successful year for Craighead Badminton. We had a lot of new players sign up, taking our total number of teams from 7 last year up to 12 this year. In the final week of play, we were competing in some big matches. While we did not win them all, we did still get some excellent results to finish off a great season.</p>
  <br />
  <h3>Some of the key results were:</h3>
  <li>Junior CDS 3 won the Junior Girls Division. This team consisted of Honour Andrews, Islabelle Taylor, Ruby Gordon, and Annabelle Talbot. They had the assistance of Riley Pawsey helping out in the final as a substitute. Even more impressive with this being their first year playing!</li>
  <li>Senior CDS 2 were runners-up in the Senior Girls B Grade Division. This team was made up of Skye Bowen, Camryn Porter, Pear Chantrasup, and Haruka Kato.</li>
  <li>Senior CDS 6 won the Senior Girls C Grade Division. This team included Samantha Giddings, Mia Donaldson, Emma Campbell, Heather Miller, and Abby McLeod.</li>
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
