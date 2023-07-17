<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Nav />
<Header title="Craighead Diocesan School" subtitle="Sports Portal" />
<main>
  <h1>Table Tennis</h1>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <p>Table Tennis is played on a Wednesday night at the Barry Butler Table Tennis Stadium on Coonoor Rd, 56.30pm to 78.00pm.</p>
      <br />
      <br />
      <h2>LEVELS</h2>
      <p>Years 9-13</p>
      <br />
      <h2>TERMS</h2>
      <p>Terms 2 and 3</p>
      <br />
      <h2>COST</h2>
      <p>$15 Monday Night Competition ($45 Team of 3)</p>
      <br />
      <h2>IMPORTANT DATES 2023</h2>
      <p>Friday 18 August - Aoraki Table Tennis</p>
      <br />
      <h2>UNIFORM</h2>
      <p>School PE Uniform</p>
      <br />
      <h2>Teacher in Charge - Mrs Surridge</h2>
    </div>
  </div>
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
  ul {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
  }
</style>
