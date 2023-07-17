<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Nav />
<Header title="Craighead Diocesan School" subtitle="Sports Portal" />
<main>
  <h1>Rowing</h1>
  <div class="columns">
    <!-- put tge images in here
     -->
    <div class="column" />
    <!-- start of second column -->
    <div class="column">
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
      <h2>Teacher in Charge - Ms Graham</h2>
    </div>
  </div>
  <h2>ROWING 2022</h2>
  <p>The Craighead rowing squad competed in the South Island Club Championships in Twizel. South Island Rowing did an incredible job of organising the 1390 rowers into 20 zones of less than 100 rowers.The squad did exceptionally well at the regatta, coming away with 4 silver and two bronze medals.</p>
  <h3>Congratulations to the following students:</h3>
  <p><strong> Silver medals</strong> – U17 quad sculls- Lucy Crawford, Elsie Talbot, Paige Butler- Baird, Kate Harrison and Mackenzie Coupland (Cox)– U17 Single – Elsie Talbot– U15 Double – Isla Crawford, Lilly Grant– U15 Octi- Annabelle Talbot, Isla Crawford, Lilly Grant, Olivia Huddleston, Carmina Canberra-Martin, Ava Yellowless, Amber Wall, Emily Caird, Mackenzie Coupland(Cox)</p>
  <p><strong> Bronze Medals </strong>- Women’s Club 8- Emma Wood, Lucy Crawford, Savanna Paul, Georgia Harrison, Bronte Murney, Jemma Bent, Kate Harrison, Kate Mackenzie, Lilou Caspritz (Cox)Novice Double- Isla Crawford, Lilly Grant</p>
  <br />
  <h3>ROWING - MAADI CUP 2022</h3>
  <p>Congratulations to our senior rowers who achieved wonderful results at this year's Maadi Cup.A total of 1 Silver and 3 Bronze medals.</p>
  <li>Nadia Van Den Bosch = U16 Single, Bronze</li>
  <li>Elsie Talbot = U18 Single, Bronze</li>
  <li>Elsie Talbot + Paige Butler-Baird = U17 Double, Silver</li>
  <li>Zoe Gordon + Chanel Gordon = Novice Double, Bronze</li>
  <br />
  <h3>SISS SECONDARY SCHOOL ROWING CHAMPIONSHIPS 2022</h3>
  <p>
    Craighead had an excellent weekend of results at the premier event in the South Island school rowing calendar, the South Island Secondary School Rowing Championships. Craighead achieved 19 A finals out of 22 crews which reflects the depth of talent in the squad. 1 gold medal, 6 silver medals and 3 bronze medals was an outstanding result.
    <br />
    <br />
    Nadia Van den Bosch claimed gold in the U16 single sculls following up from her success in the same event at the South Island junior regatta two weekends ago. She is looking in excellent form going into the Maadi Cup regatta, the final regatta in the secondary school’s calendar at the end of March. Zoe Gordon joined Nadia to win silver in the U16 double sculls event.
    <br />
    <br />
    The U15 Octuple, Annabelle Talbot, Isla Crawford, Lilly Grant, Emily Caird, Carmina Cabrera, Olivia Huddleston, Amber Wall, Ava Yellowlees and Mackenzie Coupland, won silver in a closely fought race, narrowly being beaten to the gold by less than half a second. This is their last race for season, as COVID number restrictions exclude this age group from competing in the Maadi Cup.
    <br />
    <br />
    Elsie Talbot continued her excellent form, winning bronze in the U17 single sculls and racing an hour later in the U18 single to claim silver. Paige Butler-Baird joined her in the U17 double sculls to also achieve silver.
    <br />
    <br />
    Chanel Gordon and Zoe Gordon, both in their first year of rowing, won silver in the highly competitive U18 Novice double race. Some excellent bronze medal results added to the Craighead medal haul. According to Head Coach Dean Milne. “This has been the most successful South Island Secondary Schools results Craighead has achieved for many years.”
  </p>

  <p><strong> Gold</strong></p>
  <li>Girls U16 Single – Nadia Van den Bosch</li>
  <br />
  <p><strong> Silver</strong></p>
  <li>Girls U18 Novice Double – Zoe Gordon and Chanel Gordon</li>
  <li>Girls U15 Octuple Sculls – Annabelle Talbot, Isla Crawford, Lilly Grant, Emily Caird, Carmina Cabrera-Martin, Olivia Huddleston, Amber Wall, Ava Yellowlees and Mackenzie Coupland</li>
  <li>Girls U18 Single – Elsie Talbot</li>
  <li>Girls U17 Double – Elsie Talbot and Paige Butler- Baird</li>
  <li>Girls U18 Novice Double – Zoe Gordon and Chanel Gordon</li>
  <li>Girls U16 Double – Nadia Van Den Bosch and Zoe Gordon</li>
  <br />
  <p><strong> Bronze</strong></p>
  <li>Girls U17 Coxed Quad – Lucy Crawford, Paige Butler Baird, Elise Talbot, Kate Harrison and Mackenzie Coupland.</li>
  <li>Girls U17 Single – Elsie Talbot</li>
  <li>Girls U15 Double – Isla Crawford and Lilly Grant</li>
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
