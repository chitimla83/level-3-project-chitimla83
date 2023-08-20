<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Cross Country</h1>
  <div class="columns">
    <!-- start of tile -->
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-11">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child">
              <Image src="/crosscountry2.png" alt="primary school cross country" />
              <Image src="/crosscountry.png" alt="senior cross country" />
            </article>
          </div>
          <!-- end of tile -->
          <div class="column" />
          <!-- start of second column -->

          <div class="column">
            <!-- start of tile s -->
            <div class="tile is-ancestor">
              <div class="tile is-parent">
                <div class="tile is-child is-6">
                  <Image src="/andrewjones.JPG" alt="placeholder" />
                </div>
                <!-- child -->
                <div class="tile is-child">
                  <h3>Teacher in Charge - Andrew Jones</h3>
                  <p>jonesan@craighead.school.nz</p>
                </div>
                <!-- child -->
              </div>
              <!-- parent  -->
            </div>
            <!-- ancestor -->
            <!-- end of new tile -->

            <h2>LEVELS</h2>
            <p>Years 7-13</p>
            <br />
            <h2>Terms 2 and 3</h2>
            <h2>COST TBD</h2>
            <br />
            <h2>IMPORTANT DATES 2023</h2>
            <p>School Cross Country - April 6</p>
            <p>Aoraki Cross Country - Tuesday 16 May, Ashbury Park, Timaru</p>
            <br />
            <h2>UNIFORM</h2>
            <p>Sports PE Top and Shorts, white socks and gymshoes</p>
            <br />
            <p>Craighead has a proud history of success and participation in athletics and developed a strong sense of 'team' in what is often perceived as an individual sport. Craighead is committed to facilitating opportunities for students to compete at a regional, South Island and national level in both athletics and cross country on an annual basis. Craighead is focused on developing talent and participation working closely with the South Canterbury Amateur Athletics Club to provide coaching opportunities for those that wish to understand more about the different disciplines. Trainings are on Mondays from 4pm at the Stadium and begin in early September.</p>
          </div>
        </div>

        <h2>SCHOOL CROSS COUNTRY 2023</h2>
        <ul>
          <li>Minor Runner Up – Charlie Nicol</li>
          <li>Minor Champion – Lily Crosbie</li>
          <li>Junior Runner Up – Ruby Mahuika</li>
          <li>Junior Champion – Kayla Allington</li>
          <li>ntermediate Runner Up – Isabella Power</li>
          <li>Intermediate Champion – Faith Coffin</li>
          <li>Senior Runner Up – Lydia Giles</li>
          <li>Senior Champion – Niamh Motley</li>
          <li>Inter Sports Cross Country Trophy - Rugby</li>
          <br />
          <h3>House Points</h3>
          <li>1st Te Raki 272</li>
          <li>2nd Te Uru 242</li>
          <li>3rd Te Tonga 221</li>
          <li>4th Te Rawhiti 209</li>
        </ul>

        <br />
        <h2>Canterbury Cross Country</h2>
        <p>
          The Canterbury Secondary School Road race was held on Monday 8 May around a flat and fast track on the footpaths through North Hagley Park in Christchurch. A team of 8 girls travelled north to give themselves some early season race experience before the main cross country event at the end of May, and in June culminating in the team travelling to the NZ Secondary Schools Cross Country being held this year in Palmerston North.
          <br />
          In their first regional race at high school level, the Year 9 team of Kayla Allington, Harriet Phillips and Milla McKenzie fought back hard from a very aggressive start, with the determined Allington then gritting her way to an outstanding 5th place overall.
          <br />
          In the Junior (Under 16) girls race, the team of Ruby Laming, Georgia Bell and Kate Caird, used their experience from last year to pace themselves, the diminutive Laming showing she was not going to be pushed around by girls a year older than her, running an outstanding race to narrowly finish third in a sprint finish for second.
          <br />
          The Senior (Under 19) girls race is an exhibition of the best female runners in the wider Canterbury region, with Canterbury runners having to compete in this and the Canterbury Secondary Schools Cross Country in order to be selected for the regional relay teams at the NZSS Cross Country. For Emily Caird and Niamh Motley it was fast paced, with the vastly experienced Motley playing the chasing game beautifully, using the leading bunch to pace her, then finishing second in devastating form.
        </p>
        <br />
        <h3>Final Results:</h3>

        <ul>
          <li>Year 9 Girls: Kayla Allington 5th; Harriet Phillips 25th; Milla McKenzie 39th.</li>
          <li>Under 16 Girls: Ruby Laming 3rd; Georgia Bell 27th; Kate Caird 28th.</li>
          <li>Under 19 Girls: Niamh Motley 2nd; Emily Caird 29th</li>
        </ul>
      </div>
    </div>
  </div>
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
</style>
