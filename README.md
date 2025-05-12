<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Social Buzz Analysis - Forage Project</title>
  <style>
    /* Global Styles */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f9fc;
      color: #333;
      line-height: 1.6;
    }

    h1, h2 {
      font-weight: bold;
      color: #004b8d;
      text-align: center;
    }

    /* Main Title */
    .main-title {
      background-color: #004b8d;
      color: #fff;
      padding: 40px;
      text-transform: uppercase;
      font-size: 3rem;
      animation: fadeIn 1s ease-out;
    }

    /* Deck Styles */
    .deck {
      max-width: 1200px;
      margin: 40px auto;
      background-color: #ffffff;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      padding: 20px;
      overflow: hidden;
      animation: slideUp 0.7s ease-out;
    }

    .deck img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .deck p {
      font-size: 1.1rem;
      color: #555;
      margin-top: 20px;
    }

    /* Section Titles */
    .deck h2 {
      font-size: 2rem;
      color: #004b8d;
      margin-bottom: 15px;
    }

    /* Animation Effects */
    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    @keyframes slideUp {
      0% {
        transform: translateY(50px);
        opacity: 0;
      }
      100% {
        transform: translateY(0);
        opacity: 1;
      }
    }

    /* Responsive Styles */
    @media (max-width: 768px) {
      .main-title {
        font-size: 2rem;
        padding: 20px;
      }

      .deck {
        margin: 20px;
        padding: 15px;
      }

      .deck img {
        width: 100%;
        height: auto;
      }
    }
  </style>
</head>
<body>

  <!-- Main Title -->
  <div class="main-title">
    <h1>Social Buzz Analysis from the Forage Project</h1>
  </div>

  <!-- Deck 1: Project Title -->
  <div class="deck" id="deck1">
    <h2>Deck 1: Project Title</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide1.PNG?raw=true" alt="Project Title">
    <p>Explanation for the project title goes here...</p>
  </div>

  <!-- Deck 2: Agenda -->
  <div class="deck" id="deck2">
    <h2>Deck 2: Agenda</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide2.PNG?raw=true" alt="Agenda">
    <p>Explanation of the agenda goes here...</p>
  </div>

  <!-- Deck 3: Project Recap -->
  <div class="deck" id="deck3">
    <h2>Deck 3: Project Recap</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide3.PNG?raw=true" alt="Project Recap">
    <p>Explanation for the project recap goes here...</p>
  </div>

  <!-- Deck 4: Problem -->
  <div class="deck" id="deck4">
    <h2>Deck 4: Problem</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide4.PNG?raw=true" alt="Problem">
    <p>Explanation for the problem goes here...</p>
  </div>

  <!-- Deck 5: The Team -->
  <div class="deck" id="deck5">
    <h2>Deck 5: The Team</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide5.PNG?raw=true" alt="The Team">
    <p>Explanation for the team goes here...</p>
  </div>

  <!-- Deck 6: Process -->
  <div class="deck" id="deck6">
    <h2>Deck 6: Process</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide6.PNG?raw=true" alt="Process">
    <p>Explanation for the process goes here...</p>
  </div>

  <!-- Deck 7: Insights -->
  <div class="deck" id="deck7">
    <h2>Deck 7: Insights</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide7.PNG?raw=true" alt="Insights">
    <p>Explanation for insights goes here...</p>
  </div>

  <!-- Deck 8: Insights -->
  <div class="deck" id="deck8">
    <h2>Deck 8: Insights</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide8.PNG?raw=true" alt="Insights">
    <p>Explanation for insights goes here...</p>
  </div>

  <!-- Deck 9: Insights -->
  <div class="deck" id="deck9">
    <h2>Deck 9: Insights</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide9.PNG?raw=true" alt="Insights">
    <p>Explanation for insights goes here...</p>
  </div>

  <!-- Deck 10: Insights -->
  <div class="deck" id="deck10">
    <h2>Deck 10: Insights</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide10.PNG?raw=true" alt="Insights">
    <p>Explanation for insights goes here...</p>
  </div>

  <!-- Deck 11: Summary -->
  <div class="deck" id="deck11">
    <h2>Deck 11: Summary</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide11.PNG?raw=true" alt="Summary">
    <p>Explanation for the summary goes here...</p>
  </div>

  <!-- Deck 12: Thank You -->
  <div class="deck" id="deck12">
    <h2>Deck 12: Thank You</h2>
    <img src="https://github.com/EdmundFrimpong/Excel-Project/blob/f49f38d4a8b1f8f257de3bfe6984c7e2a20fc443/Slide12.PNG?raw=true" alt="Thank You">
    <p>Thank you for your attention! Let me know if you have any questions.</p>
  </div>

</body>
</html>
