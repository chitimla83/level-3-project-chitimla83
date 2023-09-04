<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <div class="tile is-ancestor section">
    <div class="tile is-parent is-vertical">
      <div class="tile is-child notification is-info">
        <h1>Welcome to the Craighead Sports Portal!</h1>
        <p>This is the page dedicated to all Sporting Achievements, Acknowledgements and Events of the girls apart of the School and its community. Please contact Mr Mulholland or Mrs Surridge about any of your achievements as soon as possible so it can be celebrated on the Sports Portal.</p>
      </div>
    </div>
  </div>

  <!-- images -->
  <div class="tile is-ancestor section">
    <div class="tile is-vertical is-12">
      <div class="tile">
        <div class="tile is-parent is-vertical">
          <article class="tile is-child notification is-info">
            <Image src="/sports.png" alt="sports collage" />
          </article>
          <!-- images -->

          <!-- buttons -->
          <br />
          <br />
          <h3>Click on the buttons to access the following</h3>

          <div class="buttons">
            <!-- Sports app button -->
            <a class="button is-info is-light is-large is-hovered" href="https://www.sporty.co.nz/asset/downloadasset?id=4c10bdeb-2e74-4349-9f27-bc488282d69a">Sporty App</a>
            <!-- handbook button  -->
            <a class="button is-info is-light is-large is-hovered" href="https://www.sporty.co.nz/asset/downloadasset?id=4f5ee77f-5ffe-4955-8070-74a1e83fbe1a">Sports Handbook</a>
            <!-- Injury or Accident form button -->
            <a class="button is-info is-light is-large is-hovered" href="https://docs.google.com/forms/d/e/1FAIpQLSfRZy6FVY7YpIaBEMFa9GvAolDDEWMWoNJ2SGRbZj4RT_DcPg/viewform">Injury or Accident form</a>
            <!-- Code of Conduct Button -->
            <a class="button is-info is-light is-large is-hovered" href="https://forms.gle/kNXDWSDWrc8kw4VS9">Code of Conduct Form for Players/Parents/Caregivers </a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- button -->
  <!-- text -->
  <br />
  <h3>General Information</h3>
  <h4>
    The School Athletics and Swimming Championships are compulsory for all girls and are held early in Term One. In both cases there is an inter-House aspect as well as the individual championships. All girls must enter at least two events for each of these competitions, either as an individual or as a team member in the various relay events. <strong> Only Year 13 girls are allowed to wear ‘mufti’ clothes or get ‘dressed up’ for these Championships; however, they must wear PE uniform or House t-shirts when competing. All other girls must wear either their normal PE uniform or their House coloured t-shirts. There are also a number of Inter-School exchanges during the year. </strong>The main exchanges are the Term 1 Summer and the Term 3 Winter Quadrangular Tournaments with our sister schools in Christchurch (Rangi Ruru Girl’s School and St. Margaret’s College) and Dunedin (Columba College and St. Hilda’s Collegiate). Exchanges are also held with St. Andrew’s College in Term 3 and with
    Rangi Ruru (Juniors only) in Term 2. Girls are asked to encourage their parents and family to support them and the School at any inter-House competitions or inter-School games during the year.
  </h4>
  <br />
  <h3>Conduct and Behaviour:</h3>
  <h4>Craighead strongly supports the principles of FairPlay and positive sporting conduct. Students’ appearance and conduct, both on and off the field of play, should be of the highest standard and reflect the pride that they have in our School.</h4>
  <br />
  <h4>Craighead Diocesan School expects our students who play Sport to:</h4>
  <br />
  <ul>
    <li>Wear the correct uniform to all games and practices and ensure that it is clean and tidy be punctual to all games and practices</li>
    <li>Abide by the referee’s/umpire’s decisions without complaint or argument</li>
    <li>Avoid inappropriate behaviour such as swearing, fighting, arguing – even when they may be provoked!</li>
    <li>Show loyalty to their team, captain, coach and School</li>
    <li>Congratulate good sporting behaviour, whether it is their own team or the opposition</li>
  </ul>
  <br />
  <h4>
    <strong> While some sports may seem more ‘competitive’ than others, all girls take their participation very seriously, with teams and individuals always performing very highly. </strong>
  </h4>
  <br />
  <h3>To Play a Sport:</h3>
  <ul>
    <li>All girls and their parents must complete appropriate sections on the <strong>CRAIGHEAD SPORTS PORTAL </strong>'online registration.</li>
    <li>Affiliations fees are charged for all extracurricular sporting activities.</li>
    <li>Teaching staff have the right to prevent students attending these activities in school time if their work is not up to date.</li>
    <li>When any girl commits herself to a team they must attend all practices and games. Where circumstances mean that girls cannot attend at any time, then the captain and coach must be informed.</li>
  </ul>
  <br />
  <h4>
    <strong> Sports practice days can be any day of the week and practice times vary with the sport, but generally they are one hour long, with the afternoon practices usually finishing by 7.30pm.</strong>
  </h4>

  <br />
  <!-- <br />
        </div>
      </div>
    </div>
  </div> -->
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
  h4 {
    font-family: "Quattrocento Sans";
    font-size: 17px;
    text-align: left;
    margin-left: 70px;
    margin-right: 20px;
  }
</style>
