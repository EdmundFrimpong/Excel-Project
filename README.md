<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Social Buzz Analysis - Forage Project</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #ffffff;
      color: #003366;
    }
    header {
      background-color: #003366;
      color: #fff;
      text-align: center;
      padding: 50px 20px;
    }
    header h1 {
      margin: 0;
      font-size: 3em;
      animation: fadeIn 2s ease-in-out;
    }
    .deck {
      padding: 40px 20px;
      max-width: 900px;
      margin: 0 auto;
      border-bottom: 1px solid #ddd;
      animation: slideUp 0.8s ease-in-out;
    }
    .deck h2 {
      font-size: 1.8em;
      color: #003366;
    }
    .deck img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 10px;
      box-shadow: 0 4px 8px rgba(0, 51, 102, 0.2);
    }
    .deck p {
      margin-top: 15px;
      font-size: 1em;
      line-height: 1.6;
    }
    @keyframes slideUp {
      from {
        transform: translateY(20px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    a {
      color: #0077cc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Social Buzz Analysis from the Forage Project</h1>
  </header>

  <!-- Decks 1 to 12 -->
  <script>
    const decks = [
      {title: "Project Title", img: "Slide1.PNG", text: "This slide introduces the Social Buzz Analysis project, outlining its purpose and significance."},
      {title: "Agenda", img: "Slide2.PNG", text: "The agenda provides a roadmap of the presentation's structure and flow."},
      {title: "Project Recap", img: "Slide3.PNG", text: "This section recaps the goals, scope, and datasets used in the project."},
      {title: "Problem", img: "Slide4.PNG", text: "Here, we define the key business problem this analysis aims to solve."},
      {title: "The Team", img: "Slide5.PNG", text: "Meet the contributors and their respective roles in the project."},
      {title: "Process", img: "Slide6.PNG", text: "An outline of the steps followed during the analysis: data gathering, cleaning, and visualization."},
      {title: "Insights", img: "Slide7.PNG", text: "Insight 1: Initial findings derived from descriptive analysis."},
      {title: "Insights", img: "Slide8.PNG", text: "Insight 2: Notable patterns in consumer engagement and behavior."},
      {title: "Insights", img: "Slide9.PNG", text: "Insight 3: Regional or temporal trends and their implications."},
      {title: "Insights", img: "Slide10.PNG", text: "Insight 4: Key metrics that support actionable recommendations."},
      {title: "Summary", img: "Slide11.PNG", text: "A summary of findings and conclusions from the project analysis."},
      {title: "Thank You", img: "Slide12.PNG", text: "Closing remarks and acknowledgments to the audience."}
    ];

    decks.forEach((deck, index) => {
      const section = document.createElement('div');
      section.className = 'deck';
      section.id = `deck${index + 1}`;
      section.innerHTML = `
        <h2>${deck.title}</h2>
        <img src="https://raw.githubusercontent.com/EdmundFrimpong/Excel-Project/main/${deck.img}" alt="${deck.title}" />
        <p>${deck.text}</p>
      `;
      document.body.appendChild(section);
    });
  </script>

  <!-- Deck 13: Project Documents -->
  <div class="deck" id="deck13">
    <h2>Project Documents</h2>
    <p>You can access the project files below:</p>
    <ul>
      <li><a href="" target="_blank">Excel Workbook</a></li>
      <li><a href="https://github.com/EdmundFrimpong/Excel-Project" target="_blank">Presentation Slides (GitHub Repository)</a></li>
    </ul>
  </div>

</body>
</html>
