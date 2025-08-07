<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raja Tirumalasetti | Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: #0b1d3a;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }
    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1.5rem;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s ease;
    }
    nav ul li a:hover {
      color: #1abc9c;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 2rem;
      color: #0b1d3a;
    }
    .card {
      background: #fff;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      margin-bottom: 2rem;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    footer {
      background: #0b1d3a;
      color: #fff;
      text-align: center;
      padding: 1.5rem;
    }
    .icon {
      margin-right: 10px;
    }
    a {
      color: #0b1d3a;
    }
  </style>
</head>
<body>
  <header>
    <h1>Raja Tirumalasetti</h1>
    <p>Computer Science Student | Python Developer | Data Analyst</p>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#internships">Internships</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <div class="card">
      <p>I'm a results-driven Computer Science undergraduate with a strong foundation in Python, Data Science, and Machine Learning. I’ve led and contributed to real-time projects such as stock market prediction and data dashboarding with Power BI. With a passion for analytics and innovation, I thrive in team-oriented environments that solve meaningful problems.</p>
    </div>
  </section>

  <section id="skills">
    <h2>Technical Skills</h2>
    <div class="card">
      <p><strong>Languages:</strong> Python, SQL, C++, HTML</p>
      <p><strong>Tools:</strong> Power BI, Excel, Pandas, NumPy, Streamlit</p>
      <p><strong>ML:</strong> Regression, ARIMA, LSTM, XGBoost, Classification, EDA</p>
      <p><strong>Domains:</strong> Data Science, Data Analytics, Software Development, Business Analysis</p>
      <p><strong>Platforms:</strong> GitHub, AWS (Virtual Internship)</p>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="card">
      <h3>Stock Market Monitoring & Price Prediction</h3>
      <ul>
        <li>Built a forecasting system using ARIMA, LSTM, and XGBoost for stock price prediction.</li>
        <li>Processed historical stock data with Pandas and visualized trends using Power BI.</li>
        <li>Integrated TensorFlow models for deep learning predictions.</li>
        <li><strong>Role:</strong> Team Lead – managed project planning, modeling, and stakeholder documentation.</li>
      </ul>
    </div>
    <div class="card">
      <h3>Spotify Top Hit Playlist Analysis</h3>
      <ul>
        <li>Cleaned and analyzed Spotify playlist data in Excel and Power BI.</li>
        <li>Created interactive dashboards displaying user preferences, artist popularity, and regional trends.</li>
        <li>Generated insights on genre distribution and listening patterns.</li>
      </ul>
    </div>
    <div class="card">
      <h3>Student Marks Prediction App (Machine Learning)</h3>
      <ul>
        <li>Built a web app using Flask and ML models to predict student marks based on study hours.</li>
        <li>Deployed using Streamlit for real-time interaction and visualization.</li>
      </ul>
    </div>
  </section>

  <section id="internships">
    <h2>Internships</h2>
    <div class="card">
      <h3>AWS Data Engineering (Virtual)</h3>
      <ul>
        <li>Explored cloud-based data pipelines and real-time processing with AWS tools.</li>
        <li>Hands-on practice with data lake, storage, ETL workflows, and AWS best practices.</li>
      </ul>
    </div>
    <div class="card">
      <h3>ICT Academy – Infosys Foundation Finishing School</h3>
      <ul>
        <li>Executed data visualization projects in Power BI transforming raw datasets into dashboards.</li>
        <li>Applied data cleaning, modeling, and DAX expressions for interactive business reporting.</li>
      </ul>
    </div>
    <div class="card">
      <h3>Amaravathi Software Innovations Pvt. Ltd. – AI Intern</h3>
      <ul>
        <li>Worked on AI-based mini projects including sentiment analysis and model deployment.</li>
        <li>Collaborated in a team to explore NLP libraries and real-world AI use cases.</li>
      </ul>
    </div>
  </section>

  <section id="education">
    <h2>Education</h2>
    <div class="card">
      <p><strong>Bachelor of Engineering (B.E.) in Computer Science</strong><br>Sri Vasavi Institute of Engineering and Technology, Nandamuru<br>CGPA: 7.99 (2021 – 2025)</p>
      <p><strong>Intermediate (MPC)</strong><br>Pavitra Co-operative Junior College, Machilipatnam<br>Percentage: 89% (2019 – 2021)</p>
      <p><strong>SSC</strong><br>Sri Chaitanya School, Challapalli<br>GPA: 9.5/10 (2018 – 2019)</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="card">
      <p><i class="fas fa-envelope icon"></i>Email: <a href="mailto:rajatirumalasetti2@gmail.com">rajatirumalasetti2@gmail.com</a></p>
      <p><i class="fab fa-linkedin icon"></i><a href="https://linkedin.com/in/raja-tirumalasetti-4578082ba" target="_blank">LinkedIn</a></p>
      <p><i class="fab fa-github icon"></i><a href="https://github.com/Raja-Tirumalasetti" target="_blank">GitHub</a></p>
      <p><i class="fas fa-phone icon"></i>Phone: +91 6301820179</p>
      <p><i class="fas fa-map-marker-alt icon"></i>Challapalli, Krishna District, Andhra Pradesh</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Raja Tirumalasetti. Designed with passion and precision.</p>
  </footer>
</body>
</html>
