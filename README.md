<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Excel Project - Slide Deck</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      overflow-x: hidden;
    }
    .slide {
      height: 100vh;
      padding: 60px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      border-bottom: 1px solid #ccc;
    }
    h1, h2 {
      color: #333;
    }
    .slide:nth-child(odd) {
      background: #f7f7f7;
    }
    .slide:nth-child(even) {
      background: #e3f2fd;
    }
  </style>
</head>
<body>
  <div class="slide">
    <h1>Excel Sales Analysis</h1>
    <p>Overview of the project and objectives</p>
  </div>

  <div class="slide">
    <h2>Data Cleaning</h2>
    <p>Removed duplicates, standardized date formats, fixed missing values</p>
  </div>

  <div class="slide">
    <h2>Pivot Table Insights</h2>
    <p>Top-performing products, monthly trends, regional breakdowns</p>
  </div>

  <div class="slide">
    <h2>Charts & Dashboard</h2>
    <p>Visual insights using bar, line, and pie charts</p>
  </div>

  <div class="slide">
    <h2>Conclusion</h2>
    <p>Recommendations based on data trends</p>
  </div>
</body>
</html>
