<script>
  import Image from "$lib/Image.svelte"
</script>

<main>
  <h1>Results</h1>

  <!-- images -->
  <div class="tile is-ancestor section">
    <div class="tile is-vertical is-12">
      <div class="tile">
        <div class="tile is-parent is-vertical">
          <article class="tile is-child notification is-info">
            <Image src="/sports.png" alt="sports collage" />
          </article>
          <!-- images -->
        </div>
      </div>
    </div>
  </div>

  <h2>Aoraki Cross Country</h2>
  <p>On Tuesday 16 May, Craighead had 21 students compete at the Aoraki Cross Country Championships at Ashbury Park, Timaru. The list of competitors with their team and individual results are as follows.</p>
  <br />
  <h3>Year 9</h3>
  <p>team of Kayla, Ruby and Harriett placed 1st overall!</p>
  <br />
  <ul>
    <li>Kayla Allington, 1st place Time:12.47.98</li>
    <li>Ruby Mahukika, 4th place Time: 14.04.72</li>
    <li>Harriett Phillips, 7th place</li>
    <li>Brooke Thompson, 8th place</li>
    <li>Megan Alexander, 10th place</li>
    <li>Jessica Box, 14th place</li>
    <li>Milla McKenzie, 15th place</li>
  </ul>
  <br />
  <h3>Junior Girls</h3>
  <p>team of Ruby, Faith and Georgia placed 1st overall!</p>
  <br />
  <ul>
    <li>Ruby Laming, 1st place Time: 12.43.54</li>
    <li>Faith Coffin, 2nd place Time: 13.21.52</li>
    <li>Georgia Bell, 7th place</li>
    <li>Abby Hurst, 10th place</li>
    <li>Ellie Flett, 12th place</li>
    <li>Lucy Flynn, 13th place</li>
    <li>Olivia Ewing, 22nd place</li>
  </ul>
  <br />
  <h3>Senior Girls</h3>
  <p>team of Niamh, Madi and Lucy placed 1st overall!</p>
  <br />
  <ul>
    <li>Niamh Motley, 1st place Time: 12.25.39</li>
    <li>Madi Thomas, 2nd place Time: 13.41.84</li>
    <li>Lucy Murphy, 3rd place Time: 13.43.29</li>
    <li>Lydia Giles, 5th place Time: 14.18.81</li>
    <li>Nadia Van Den Bosch, 6th place Time: 14.43.11</li>
    <li>Orla Motley, 9th place</li>
    <li>Emily Carid, 10th place</li>
  </ul>
  <br />
  <p>Congratulations to the Craighead teams for placing first in all three grades!</p>
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
