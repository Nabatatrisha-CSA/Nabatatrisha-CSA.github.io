<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trisha Nabata | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Reset & basic styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #2563EB;
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 20px 0;
      background-color: #1e40af;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #fcd34d;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #2563EB;
    }

    .about, .projects, .contact {
      margin-bottom: 50px;
    }

    .projects .project {
      background-color: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      background-color: #2563EB;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    .contact a:hover {
      background-color: #1e40af;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #1e40af;
      color: white;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Trisha Nabata</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I'm Trisha Nabata, a passionate web developer who loves creating modern and user-friendly websites. I enjoy turning ideas into interactive digital experiences and constantly learning new technologies.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>My Projects</h2>

    <div class="project">
      <h3>Project One</h3>
      <p>A brief description of your project goes here. You can include the technologies used and the goal of the project.</p>
    </div>

    <div class="project">
      <h3>Project Two</h3>
      <p>A brief description of your project goes here. You can include the technologies used and the goal of the project.</p>
    </div>

  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Feel free to reach out through any of the platforms below:</p>
    <a href="mailto:your.email@example.com">Email</a>
    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/yourprofile/" target="_blank">LinkedIn</a>
  </section>

  <footer>
    &copy; 2026 Trisha Nabata. All rights reserved.
  </footer>

</body>
</html>
