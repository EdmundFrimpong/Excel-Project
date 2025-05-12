<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Social Buzz Analysis - Forage Project</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #ffffff;
      color: #003366;
      overflow-x: hidden;
    }

    header {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 60px 20px;
      font-size: 2.5em;
      font-weight: bold;
      letter-spacing: 1px;
      animation: fadeInDown 1s ease-in-out;
    }

    .deck {
      padding: 60px 20px;
      text-align: center;
      border-bottom: 1px solid #e0e0e0;
      background-color: #f8fbff;
      animation: fadeIn 1s ease-in-out;
    }

    .deck:nth-child(even) {
      background-color: #e6f0fa;
    }

    .deck h2 {
      font-size: 1.8em;
      margin-bottom: 20px;
      color: #003366;
    }

    .deck img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
      transition: transform 0.3s ease;
    }

    .deck img:hover {
      transform: scale(1.03);
    }

    .deck p {
      font-size: 1.1em;
      max-width: 800px;
      margin: 0 auto;
      line-height: 1.6;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-40px); }
      to { opacity: 1; transform: translateY(0); }
    }

    a {
      color: #0074cc;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>
  <header>
    Social Buzz Analysis from the Forage Project
  </header>

  <!-- Sample Deck 1 - Replace these with your PNGs -->
  <div class="deck" id="deck1">
    <h2>Deck 1: Project Title</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide1.PNG?raw=true" alt="Project Title">
    <p>Social Buzz Analysis explores engagement and insights drawn from social media datasets using Excel tools.</p>
  </div>

  <!-- Repeat for Deck 2 through Deck 13 just like this -->
  <!-- Be sure to update slide numbers and text as needed -->

  <!-- Deck 13: Project Documents -->
  <div class="deck" id="deck13">
    <h2>Deck 13: Project Documents</h2>
    <p>You can download the files below:</p>
    <p><a href="https://1drv.ms/x/c/af5078129484b3f9/EdMO3dM3mGpFoPiR6KhqGrMBt6Q_KsqR3CFpMLwT8TqTUw?e=vwV7Df" target="_blank">📊 Download Excel File</a></p>
    <p><a href="https://github.com/EdmundFrimpong/Excel-Project" target="_blank">📽️ View PowerPoint Decks on GitHub</a></p>
  </div>
</body>
</html>
