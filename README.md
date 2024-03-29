
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ramanidevi R - Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    /* Additional styles for 3D animation */
    .container {
      perspective: 1000px;
    }

    .card {
      position: relative;
      width: 100%;
      height: 100%;
      transition: transform 0.8s;
      transform-style: preserve-3d;
    }

    .card:hover {
      transform: rotateY(180deg);
    }

    .front,
    .back {
      position: absolute;
      width: 100%;
      height: 100%;
      backface-visibility: hidden;
    }

    .front {
      background-color: #f7f7f7;
    }

    .back {
      background-color: #ddd;
      transform: rotateY(180deg);
    }

    .back img {
      width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ramanidevi R</h1>
    <p>Data Analytics | Data Science | SQL | Python</p>
  </header>

  <div class="container">
    <div class="card">
      <div class="front">
        <h2>Profile</h2>
        <p>As a final year postgraduate, I'm passionate about data analytics, data science, SQL, and Python. My objective is to apply my skills and mindset to contribute effectively in a dynamic professional environment. I aim to solve real-world problems, extract insights from complex datasets, and drive informed decision-making.</p>
      </div>
      <div class="back">
        <h2>Education</h2>
        <ul>
          <li>M.Sc. Mathematics - PSGR KRISHNAMMAL COLLEGE FOR WOMEN, COIMBATORE. (2022 - Ongoing)</li>
          <li>B.Sc. Mathematics - V.V. VANNIAPERUMAL COLLEGE FOR WOMEN, VIRUDHUNAGAR (March 2019)</li>
          <li>HIGHER SECONDARY - PACR AMMANI AMMAL GIRL’S HIGHER SECONDARY SCHOOL, RAJAPALAYAM (2019 -2022)</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="card">
      <div class="front">
        <h2>Projects</h2>
        <ul>
          <li><a href="#northwind-traders">Northwind Traders using Tableau</a></li>
          <li><a href="#heart-disease-data">Heart Disease Data using Tableau</a></li>
          <li><a href="#airline-passenger-satisfaction">Airline Passenger Satisfaction Dashboard using Power BI</a></li>
          <li><a href="#bike-profit-analysis">Bike Profit Analysis Dashboard using Power BI</a></li>
          <li><a href="#heart-health-data">Tracking Heart Health Data by using Excel</a></li>
          <li><a href="#bike-profit-analysis-excel">Bike Profit Analysis Dashboard using Excel</a></li>
          <li><a href="#maven-movies">Data Exploration of Maven Movies by using SQL</a></li>
          <li><a href="#motor-vehicle-thefts">Data Exploration of Motor Vehicle Thefts by using SQL</a></li>
          <li><a href="#diabetes-dataset">Solving the Diabetes Dataset Using Python</a></li>
          <li><a href="#covid-19-dataset">Predict COVID-19 Dataset Using Python</a></li>
        </ul>
      </div>
      <div class="back">
        <h2>Project Views</h2>
        <div id="northwind-traders">
          <h3>Northwind Traders using Tableau</h3>
          <p>Project view here with image</p>
          <img src="northwind-traders-image.jpg" alt="Northwind Traders Project Image">
        </div>
        <!-- Repeat similar sections for other projects -->
      </div>
    </div>
  </div>

  <section id="certifications">
    <h2>Certifications</h2>
    <ul>
      <li>Job Oriented Course - Data Science, R Programming, and Tableau</li>
      <li>Coursera - Introduction to Statistics</li>
      <li>Coursera - Fibonacci Numbers and the Golden Ratio</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>
      Phone: +91 637925028<br>
      Email: rramanidevi01@gmail.com<br>
      LinkedIn: <a href="#" target="_blank">www.linkedin.com/in/ramanidevi-ragupathy-01081528b</a><br>
      Location: Virudhunagar, Tamil Nadu<!DOCTYPE html>
    </p>
  </section>

  <footer>
    <p>&copy; 2024 Ramanidevi R</p>
  </footer>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <script src="script.js"></script>
</body>
</html>
