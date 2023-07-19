<template>
<div>

    <nav class="navbar">
      <div class="logo-section">
        <a href="#">
          <img src="@/assets/valo-logo.png" alt="Logo" img class="logo">
        </a>
      </div>
    </nav>

    <div class="circle-section">
      <!-- Circle 1 -->
      <div class="circle">
        <a href="#">
          <img src="@/assets/eloboost.png" alt="Circle Image 1">
        </a>
        <p style="font-size:20px; font-weight:bold">Elo <br> Boost</p>
      </div>

      <!-- Circle 2 -->
      <div class="circle">
        <a href="#">
          <img src="@/assets/duo.png" alt="Circle Image 2">
        </a>
        <p style="font-size:20px; font-weight:bold">Duo <br> Boost</p>
      </div>

      <div class="circle">
        <a href="#">
          <img src="@/assets/win.png" alt="Circle Image 3">
        </a>
        <p style="font-size:20px; font-weight:bold">Win <br> Boost</p>
      </div>

      <div class="circle">
        <a href="#">
          <img src="@/assets/radiant.png" alt="Circle Image 4">
        </a>
        <p style="font-size:20px; font-weight:bold">Radiant <br> Boost</p>
      </div>

      <div class="circle">
        <a href="#">
          <img src="@/assets/unranked.png" alt="Circle Image 5">
        </a>
        <p style="font-size:20px; font-weight:bold">Normal <br> Maç</p>
      </div>

      <div class="circle">
        <a href="#">
          <img src="@/assets/ilk-10.png" alt="Circle Image 6">
        </a>
        <p style="font-size:20px; font-weight:bold">Yerleştirme <br> Maçları</p>
      </div>

    </div>

    

  </div>
</template>

<script>
export default {} // No script functionality required for this component
</script>

<style>

body {
    margin: 0;
    padding: 0;
  }

.navbar {
    height: 350px; /* Set the height of the navbar */
    display: flex;
    align-items: center;
  }

  /* Styling for the logo section inside the navbar */
  .logo-section {
    background-image: url("@/assets/background.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    
    /* Set dimensions for the logo section */
    width: 100%; /* Make the logo section span the entire row */
    height: 100%; /* Make the logo section take the full height of the navbar */
    display: flex; /* Use flexbox to align the logo to the top left */
  }

  .logo{
    margin-top: 10px;
    height: 80px;
    width: 120px;
    display: flex; /* Use flexbox to align the logo to the top left */

  }
  .circle-section {
    display: flex;
    justify-content: space-around; /* Distribute circles evenly along the row */
    margin-top: 20px; /* Add some space between the navbar and circle section */
  }

  /* Styling for each circle */
  .circle {
    text-align: center;
    transition: transform 0.2s ease;
  }

  .circle img {
    height: 150px; /* Set the height of the circle image */
    width: 150px; /* Set the width of the circle image */
    border-radius: 50%; /* Make the image circular */
    transition: transform 0.2s ease;
  }

  .circle:hover img {
    transform: scale(1.1); /* Scale up the image by 10% on hover */
  }

  .circle p {
    margin-top: 10px; /* Add some space between the circle image and the word */
  }
</style>
