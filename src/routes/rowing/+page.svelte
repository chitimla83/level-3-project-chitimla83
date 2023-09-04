<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Rowing</h1>

  <!-- start of tile s -->
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child is-3">
        <Image src="/Graham L.JPG" alt=" Ms Graham" />
      </div>
      <!-- child -->
      <div class="tile is-child">
        <h3>
          Teacher in Charge - Ms Graham
          <br />
          principal@craighead.school.nz
        </h3>
      </div>
      <!-- child -->
    </div>
    <!-- parent  -->
  </div>
  <!-- ancestor -->
  <!-- end of new tile -->
  <p>
    Rowing at Craighead has existed since 1997. Coached for the past 16 years by Dean Milne, the Rowing Group are very fortunate to have a coach of his calibre and commitment especially given his input is purely voluntary.
    <br />
    <br />
    Parent involvement is essential and the key factor for the group flourishing. Craighead Rowing takes pride in its association with the school acting as ambassadors and representing the school culture and sporting ethics. The other key relationship is with Timaru Rowing Club to which the Craighead group is affiliated. The TRC is the official link to Rowing NZ and also provides the facilities at Saltwater Creek.
    <br />
    <br />
    Craighead Rowing in association with the school own 10 rowing boats, 2 chase boats, a boat trailer, 7 ergs and various other equipment.
    <br />
    <br />
    Rowing provides the girls with fantastic organisational skills which they use to ensure they maintain their school subject results whilst training and competing at rowing regattas from September to April. They are physically and mentally fit and enjoy the close relationships they form with the entire squad.
    <br />
    <br />
    During Terms 1 and 4, training camps and regettas are held at weekends. Training occurs after school and early in the mornings. Craighead attends the Maadi Cup.
  </p>
  <br />
  <br />
  <!-- link to results -->
  <!-- start button -->
  <div class="buttons">
    <a class="button is-info is-light is-large is-hovered" href="rowingresults">Rowing Results</a>
  </div>
  <!-- end of button -->
  <br />
  <br />
  <br />
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
  .is-child {
    display: flex !important;
    align-items: center !important;
  }
  div {
    margin-left: 40px;
  }
</style>
