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
    <div class="column">
      <!-- start of first column -->
      <h1>Individual Sports</h1>
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="athletics">Athletics</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="crosscountry">Cross Country</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="equestrian">Equestrian</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="mountainbiking">Mountain Biking</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="skiingandsnowboarding">Skiing and Snowboarding</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="swimming">Swimming</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="tabletennis">Table Tennis</a>
      </div>
      <!-- end of button -->
    </div>

    <!-- the start of the second column -->
    <div class="column">
      <h1>Team Sports</h1>
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="badminton">Badminton</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="basketball">Basketball</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="cricket">Cricket</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="football">Football</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="hockey">Hockey</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="netball">Netball</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="skiingandsnowboarding">Skiing and Snowboarding</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="rowing">Rowing</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="rugby">Rugby</a>
      </div>
      <!-- end of button -->

      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="shooting">Shooting</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="tabletennis">Table Tennis</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="squash">Squash</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="tennis">Tennis</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="touch">Touch</a>
      </div>
      <!-- end of button -->
      <!-- start button -->
      <div class="buttons">
        <a class="button is-info is-light is-large is-hovered" href="volleyball">Volleyball</a>
      </div>
      <!-- end of button -->
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
  a {
    font-family: "Quattrocento Sans";
    font-size: 20px;
  }

  button {
    width: fit-content;
    margin-left: auto;
    margin-right: auto;
  }
</style>
