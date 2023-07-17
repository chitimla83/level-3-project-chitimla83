<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Nav />
<Header title="Craighead Diocesan School" subtitle="Sports Portal" />

<main>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
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
      <h2>Teacher in Charge - Mr Townshend</h2>
      <br />
      <p>Football is played on a Thursday afternoon at various football grounds in Timaru. The A team comp</p>
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
</style>
