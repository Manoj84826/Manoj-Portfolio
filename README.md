<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Manoj | Data Scientist Portfolio</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      scroll-behavior:smooth;
    }

    body{
      font-family:'Poppins',sans-serif;
      background:#0f172a;
      color:white;
      line-height:1.6;
    }

    header{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
      background:linear-gradient(135deg,#0f172a,#1e293b,#334155);
    }

    .hero h1{
      font-size:4rem;
      font-weight:700;
    }

    .hero h2{
      color:#38bdf8;
      margin-top:10px;
      font-size:2rem;
      font-weight:500;
    }

    .hero p{
      max-width:700px;
      margin:20px auto;
      color:#cbd5e1;
      font-size:1.1rem;
    }

    .btn{
      display:inline-block;
      margin-top:20px;
      padding:12px 30px;
      border-radius:30px;
      background:#38bdf8;
      color:#0f172a;
      text-decoration:none;
      font-weight:600;
      transition:0.3s;
    }

    .btn:hover{
      background:white;
      transform:translateY(-3px);
    }

    section{
      padding:80px 10%;
    }

    .section-title{
      font-size:2.5rem;
      margin-bottom:40px;
      color:#38bdf8;
      text-align:center;
    }

    .card{
      background:#1e293b;
      padding:25px;
      border-radius:20px;
      margin-bottom:25px;
      transition:0.3s;
      box-shadow:0 5px 20px rgba(0,0,0,0.2);
    }

    .card:hover{
      transform:translateY(-5px);
    }

    .card h3{
      color:#ffffff;
      margin-bottom:10px;
    }

    .card span{
      color:#94a3b8;
      font-size:0.95rem;
    }

    .skills{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:20px;
    }

    .skill-box{
      background:#1e293b;
      padding:20px;
      border-radius:15px;
      text-align:center;
      font-weight:500;
      transition:0.3s;
    }

    .skill-box:hover{
      background:#38bdf8;
      color:#0f172a;
      transform:scale(1.05);
    }

    footer{
      text-align:center;
      padding:30px;
      background:#020617;
      color:#94a3b8;
    }

    @media(max-width:768px){

      .hero h1{
        font-size:2.7rem;
      }

      .hero h2{
        font-size:1.5rem;
      }

      section{
        padding:60px 7%;
      }
    }
  </style>
</head>

<body>

  <!-- HERO SECTION -->

  <header>
    <div class="hero">
      <h1>Manoj Kumar</h1>
      <h2>Data Scientist</h2>

      <p>
        Passionate Data Science student with strong knowledge in
        Machine Learning, Data Visualisation, Python, SQL and Medical
        Image Analysis. Focused on solving real-world problems using
        AI-driven solutions and data analytics.
      </p>

      <a href="#projects" class="btn">View Projects</a>
    </div>
  </header>

  <!-- EDUCATION -->

  <section id="education">

    <h2 class="section-title">Education</h2>

    <div class="card">
      <h3>MSc in Data Science</h3>
      <span>Arden University | Berlin, Germany | Pursuing</span>
    </div>

    <div class="card">
      <h3>B.Tech – Electronics & Communication Engineering</h3>
      <span>
        JNTU Hyderabad – Malla Reddy Institute of Technology and Science
        <br>
        2017 – 2023 | 65%
      </span>
    </div>

  </section>

  <!-- PROJECTS -->

  <section id="projects">

    <h2 class="section-title">Projects</h2>

    <div class="card">
      <h3>Medical Image Analysis using Machine Learning</h3>

      <p>
        Currently conducting thesis research on comparative Machine Learning
        techniques for medical image analysis with a focus on lung disease detection.
      </p>
    </div>

    <div class="card">
      <h3>Flight Price Prediction System</h3>

      <p>
        Developed and implemented Machine Learning models using real-world datasets
        to predict airline ticket prices with improved analytical accuracy.
      </p>
    </div>

    <div class="card">
      <h3>Data Visualisation Projects</h3>

      <p>
        Built multiple data visualisation dashboards and reports by transforming
        complex datasets into meaningful and actionable insights.
      </p>
    </div>

    <div class="card">
      <h3>Python & SQL Data Analytics</h3>

      <p>
        Utilised Python and SQL for data cleaning, analysis, modelling and
        interpretation of large datasets using statistical techniques.
      </p>
    </div>

  </section>

  <!-- SKILLS -->

  <section id="skills">

    <h2 class="section-title">Core Skills</h2>

    <div class="skills">

      <div class="skill-box">Python</div>
      <div class="skill-box">SQL</div>
      <div class="skill-box">Machine Learning</div>
      <div class="skill-box">Data Visualisation</div>
      <div class="skill-box">Artificial Intelligence</div>
      <div class="skill-box">Neural Networks</div>
      <div class="skill-box">Big Data & Cloud Computing</div>
      <div class="skill-box">Programming for Data Analytics</div>
      <div class="skill-box">Mathematics for Data Science</div>
      <div class="skill-box">Academic Writing</div>

    </div>

  </section>

  <!-- ACADEMIC MODULES -->

  <section id="modules">

    <h2 class="section-title">Academic Modules</h2>

    <div class="card">
      <p>
        • Artificial Intelligence and Neural Networks <br>
        • Big Data and Cloud Computing <br>
        • Data Visualisation <br>
        • Machine Learning <br>
        • Mathematics for Data Science <br>
        • Programming for Data Analytics <br>
        • Academic Writing in English 2 (UK) <br>
        • Academic Writing in English 1 (Berlin)
      </p>
    </div>

  </section>

  <!-- FOOTER -->

  <footer>
    <p>© 2026 Manoj Kumar | Data Scientist Portfolio</p>
  </footer>

</body>
</html>
