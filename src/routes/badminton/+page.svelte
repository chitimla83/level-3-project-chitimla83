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
  ul {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
  }
</style>
