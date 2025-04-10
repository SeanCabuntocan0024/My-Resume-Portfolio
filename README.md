<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Resume Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(to right, #74ebd5, #acb6e5);
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #fff;
      padding: 20px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      text-decoration: none;
      color: #333;
      margin: 0 15px;
      font-weight: 600;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .hero {
      text-align: center;
    }

    .hero img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 3px solid #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }

    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2em;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .project-card:hover {
      transform: translateY(-5px);
    }

    .statement {
      background: #f7f7f7;
      border-left: 5px solid #4a90e2;
      padding: 20px;
      border-radius: 5px;
    }

    .skills ul {
      list-style-type: square;
      padding-left: 20px;
    }

    .education {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    footer {
      background-color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>

<body>
  <header>
    <nav>
      <div><strong>My Resume</strong></div>
      <div>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#education">Education</a>
        <a href="#statement">Reflection</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <section class="hero" id="about">
    <img src="images/pic1.jpg" alt="Profile Picture" />
    <h1>Hello, I'm Sean Jesse L. Cabuntocan</h1>
    <p>A passionate IT student learning web development!</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <ul>
        <li>HTML5, CSS3, JavaScript</li>
        <li>Responsive Web Design</li>
        <li>Basic Git & GitHub</li>
        <li>UI/UX Fundamentals</li>
        <li>Problem-Solving and Debugging</li>
      </ul>
    </div>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Simple Calculator</h3>
        <p>A basic calculator using HTML, CSS, and JavaScript.</p>
      </div>
      <div class="project-card">
        <h3>Personal Blog Layout</h3>
        <p>A static blog site with responsive design.</p>
      </div>
      <div class="project-card">
        <h3>Login Form</h3>
        <p>A user-friendly login form with input validations.</p>
      </div>
    </div>
  </section>

  <section id="education">
    <h2>Education</h2>
    <div class="education">
      <p><strong>Our Lady of Fatima University</strong></p>
      <p>Bachelor of Science in Information Technology</p>
      <p>1st Year Student | 2025 - Present</p>
    </div>
  </section>

  <section id="statement">
    <h2>Personal Reflection</h2>
    <div class="statement">
      <p>
        As a first-year IT student, this journey into web development has been both challenging and rewarding to me. I have learned how to structure web pages, style them creatively, and even add interactivity using JavaScript. My projects show how much I've grown since the beginning of the semester. I aim to improve further by exploring backend technologies and creating full-stack applications. My goal is to become a versatile and creative web developer.
      </p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>📘 Facebook: Sean Cabuntocan</p>
    <p>📧 Email: slcabuntocan0024qc@student.fatima.edu.ph</p>
    <p>📱 Phone Number: 09949088059</p>
    <p>🐱 GitHub: <a href="https://github.com/SeanCabuntocan0024" target="_blank">SeanCabuntocan0024</a></p>
  </section>

  <footer>
    &copy; 2025 Sean Jesse L. Cabuntocan | 1st Year IT Student | All rights reserved.
  </footer>
</body>

</html>
