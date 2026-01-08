
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trisha Nabata | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #000;
      color: #fff;
      line-height: 1.6;
    }

    header {
      height: 400px;
      background: url('your-profile.jpg') center/cover no-repeat; /* Your profile picture here */
      position: relative;
      color: white;
    }

    header div {
      background-color: rgba(0, 0, 0, 0.6); /* Dark overlay for readability */
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-size: 2.5rem;
      color: #00BFFF;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 20px 0;
      background-color: #222;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00BFFF;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #00BFFF;
    }

    .about, .projects, .contact {
      margin-bottom: 50px;
    }

    .projects .project {
      background-color: #111;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.5);
    }

    .projects .project h3 {
      color: #00BFFF;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      background-color: #00BFFF;
      color: #000;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    .contact a:hover {
      background-color: #009ACD;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #111;
      color: #ccc;
    }
  </style>
</head>
<body>

  <!-- Header with profile image background -->
  <header>
    <div>
      <h1>Trisha Nabata</h1>
      <p>Web Developer | Designer | Tech Enthusiast</p>
    </div>
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
