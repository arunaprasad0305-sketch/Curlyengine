<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aruna Portfolio</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background:#f4f7fb;
      color:#333;
      line-height:1.6;
    }

    header{
      background:linear-gradient(135deg,#4f46e5,#7c3aed);
      color:white;
      padding:60px 20px;
      text-align:center;
    }

    header h1{
      font-size:3rem;
      margin-bottom:10px;
    }

    header p{
      font-size:1.2rem;
      opacity:0.9;
    }

    nav{
      background:white;
      padding:15px;
      text-align:center;
      box-shadow:0 2px 5px rgba(0,0,0,0.1);
      position:sticky;
      top:0;
    }

    nav a{
      margin:0 15px;
      text-decoration:none;
      color:#4f46e5;
      font-weight:bold;
    }

    section{
      padding:60px 20px;
      max-width:1000px;
      margin:auto;
    }

    .card-container{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:20px;
      margin-top:30px;
    }

    .card{
      background:white;
      padding:25px;
      border-radius:15px;
      box-shadow:0 5px 15px rgba(0,0,0,0.08);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-5px);
    }

    .btn{
      display:inline-block;
      margin-top:20px;
      padding:12px 24px;
      background:#4f46e5;
      color:white;
      border-radius:8px;
      text-decoration:none;
    }

    footer{
      background:#111827;
      color:white;
      text-align:center;
      padding:20px;
      margin-top:40px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Aruna Prasad</h1>
    <p>BCA Student | Python | SQL | Data Analytics</p>
    <a href="#projects" class="btn">View Projects</a>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Hello! I am Aruna Prasad, a BCA 3rd year student passionate about
      web development, Python programming, SQL, and data analytics.
      I enjoy creating beautiful websites and learning new technologies.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>

    <div class="card-container">
      <div class="card">
        <h3>Python</h3>
        <p>Data analysis, scripting, and automation projects.</p>
      </div>

      <div class="card">
        <h3>SQL</h3>
        <p>Database management and query optimization.</p>
      </div>

      <div class="card">
        <h3>HTML & CSS</h3>
        <p>Responsive and modern website design.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <div class="card-container">
      <div class="card">
        <h3>Sales Dashboard</h3>
        <p>Interactive dashboard using Excel and Power BI.</p>
      </div>

      <div class="card">
        <h3>Portfolio Website</h3>
        <p>Personal responsive portfolio hosted on GitHub.</p>
      </div>

      <div class="card">
        <h3>Student Database</h3>
        <p>SQL-based student record management system.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: aruna@example.com</p>
    <p>LinkedIn: linkedin.com/in/arunaprasad</p>

    <a href="https://github.com/" class="btn">
      Visit GitHub
    </a>
  </section>

  <footer>
    <p>© 2026 Aruna Prasad | Designed with HTML & CSS</p>
  </footer>

</body>
</html>
