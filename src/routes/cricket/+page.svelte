<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Nav />
<Header title="Craighead Diocesan School" subtitle="Sports Portal" />
<main>
  <h1>Cricket</h1>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <h2>LEVELS</h2>
      <p>Years 7-13</p>
      <br />
      <h2>TERMS</h2>
      <p>Terms 1</p>
      <br />
      <h2>UNIFORM</h2>
      <p>School Shorts, sleeved PE top,</p>
      <br />
      <h2>​Teacher in Charge - Mr Mulholland</h2>
      <br />
    </div>
  </div>

  <h2>Women's Quick Smash Cricket</h2>
  <li>All games are being played on a Monday night at Ashbury Park</li>
  <li>Runs for 6 consecutive Monday evenings</li>
  <li>8 females per side</li>
  <li>12 overs per side</li>
  <li>Wides and no balls worth 1 run each</li>
  <li>Batters bat in pairs</li>
  <li>Each batting pair bats for 3 overs</li>
  <li>Loss of a wicket means 6 runs taken off score</li>
  <li>Each player has to bowl at least 1 over</li>
  <li>Incrediball used, no need for pads or helmets</li>
  <li>Plastic stumps or wooden springback stumps to be used</li>
  <li>No cost to enter</li>
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
