<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Equestrian</h1>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
      <!-- start of tile s -->
      <div class="tile is-ancestor">
        <div class="tile is-parent">
          <div class="tile is-child is-4">
            <Image src="/placeholder.png" alt="Katie Mackenzie" />
          </div>
          <!-- child -->
          <div class="tile is-child">
            <h2>Teacher in Charge - Katie Mackenzie</h2>
            <p>mackenzieka@craighead.school.nz</p>
          </div>
          <!-- child -->
        </div>
        <!-- parent  -->
      </div>
      <!-- ancestor -->
      <!-- end of new tile -->

      <h2>LEVELS</h2>
      <p>Year 7-13</p>
      <br />
      <h2>TERMS</h2>
      <p>Terms 2 and 3</p>
      <br />
      <h2>COST TBD</h2>
      <br />
      <p>
        Two Craighead equestrian teams has a fantastic day recently at the South Canterbury Pony Clubs Sandalwood Trophy Interschools Dressage and Show Jumping competition.
        <br />
        Craighead had individual placegetters in both Dressage and Showjumping and the Blue team of Cate Lightbourne, Lydia Hanrahan, Greta Dale, Sophie Martin and Eve Andrews were placed second overall.
        <br />
        Green team were Maggie Moore, Greta Murray, Annabelle Murray, Zoe Dupont and Sophie Smith.
      </p>
    </div>
  </div>

  <p>
    Meg Johnston has been competing at the Dressage 4 Denmark FEI CDI/CDI-Y in Taupo last week. She had a very successful show winning Champion FEI Young Rider!
    <br /> Congratulations Meg and Harry!
  </p>
  <br />
  <p>
    Members of the Craighead Equestrian team recently competed in the Secondary Schools Canterbury One Day Event at McLeans Island. We had two teams – CDS Blue Cate Lightbourne, Lydia Hanrahan, Sophie Smith and Annabel Murray and CDS Green which was also a composite team of Abi Hyslop, Poppy Slater and riders from Middleton Grange and Riccarton High.
    <br />
    Congratulations to the CDS Green Team of Abi Hyslop, Poppy Slater, Mischa Vaughan ( R. H.S) and Nicole Irving ( M.G) on coming 5th overall. Some excellent dressage and cross country riding in what was a very wet, cold and trying day.
    <br />
    CDS Blue started well and Cate Lightbourne and Sophie Smith finished the day on their dressage scores but the cross-country component was not to be for Lydia Hanrahan and Annabel Murray, resulting in eliminations.
  </p>
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
