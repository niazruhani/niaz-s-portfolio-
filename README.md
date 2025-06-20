<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Niaz Ruhani | Frontend Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {
      font-family: 'Poppins', sans-serif;
      background: #f5f7fa;
      color: #333;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 40px 0;
      text-align: center;
    }
    header h1 {
      font-size: 36px;
    }
    header p {
      font-size: 18px;
    }
    section {
      max-width: 1000px;
      margin: 50px auto;
      padding: 20px;
    }
    .about, .skills, .projects, .contact {
      background: white;
      border-radius: 15px;
      padding: 30px;
      margin-bottom: 30px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
    }
    .about img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 3px solid #007bff;
      object-fit: cover;
      display: block;
      margin: 0 auto 20px;
    }
    h2 {
      color: #007bff;
      margin-bottom: 15px;
    }
    .skills-bar {
      margin-bottom: 15px;
    }
    .skills-bar label {
      display: block;
      font-weight: bold;
      margin-bottom: 5px;
    }
    .bar {
      background: #e0e0e0;
      border-radius: 30px;
      overflow: hidden;
    }
    .bar-fill {
      height: 20px;
      background: #007bff;
      width: 0%;
      text-align: right;
      color: white;
      padding-right: 10px;
      line-height: 20px;
      transition: width 1s ease-in-out;
    }
    .projects .project {
      background: #f0f8ff;
      padding: 15px;
      margin: 15px 0;
      border-left: 5px solid #007bff;
      border-radius: 5px;
    }
    .contact a {
      text-decoration: none;
      color: white;
      background: #1877f2;
      padding: 10px 20px;
      border-radius: 8px;
      display: inline-block;
      margin-top: 15px;
    }
    footer {
      background: #007bff;
      text-align: center;
      color: white;
      padding: 20px 0;
      font-size: 14px;
    }
  </style>
</head>
<body onload="animateSkills()">

  <header>
    <h1>Niaz Ruhani</h1>
    <p>Frontend & Web Developer | HTML, CSS, JavaScript, React</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <img src="https://drive.google.com/uc?export=view&id=1fVIVu-SOhU1IoAOzJdXl5WDsnZzjGTOZ" alt="Niaz Ruhani">
    <p>Hello! I’m a passionate Frontend Web Developer from Satkhira, Dhaka, Bangladesh. I love building beautiful and functional websites using modern web technologies like React, HTML, CSS, and JavaScript. My goal is to become a full-stack developer and build impactful digital solutions.</p>
  </section>

  <section class="skills">
    <h2>My Skills</h2>
    <div class="skills-bar">
      <label>HTML</label>
      <div class="bar"><div class="bar-fill" data-width="95%">95%</div></div>
    </div>
    <div class="skills-bar">
      <label>CSS</label>
      <div class="bar"><div class="bar-fill" data-width="90%">90%</div></div>
    </div>
    <div class="skills-bar">
      <label>JavaScript</label>
      <div class="bar"><div class="bar-fill" data-width="85%">85%</div></div>
    </div>
    <div class="skills-bar">
      <label>React</label>
      <div class="bar"><div class="bar-fill" data-width="80%">80%</div></div>
    </div>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>A responsive and animated personal portfolio website built with HTML, CSS, and JavaScript.</p>
    </div>
    <div class="project">
      <h3>Weather App</h3>
      <p>A weather application using OpenWeather API and JavaScript that shows real-time weather info.</p>
    </div>
    <div class="project">
      <h3>React To-Do List</h3>
      <p>A modern to-do list app built with React that supports CRUD functionality.</p>
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Feel free to connect with me on Facebook!</p>
    <a href="https://www.facebook.com/share/1Fo7bXhdMt/" target="_blank">Message Me on Facebook</a>
  </section>

  <footer>
    &copy; 2025 Niaz Ruhani | All Rights Reserved
  </footer>

  <script>
    function animateSkills() {
      const bars = document.querySelectorAll('.bar-fill');
      bars.forEach(bar => {
        const width = bar.getAttribute('data-width');
        bar.style.width = width;
      });
    }
  </script>
</body>
</html># niaz-s-portfolio-
