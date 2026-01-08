<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trisha Nabata Portfolio</title>
  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: 'Treasure Map Deadhand', Arial, sans-serif;
      background: #0b0c10; /* deep space background */
      color: #fff;
    }

    /* Header */
    header {
      background: url('https://images.unsplash.com/photo-1581091215366-7ecbf2b1a1f2?auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    header h1 {
      font-size: 3em;
      text-shadow: 2px 2px 10px #00f;
    }
    header p {
      font-size: 1.2em;
      text-shadow: 1px 1px 8px #0ff;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: center;
      background: #1f2833;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 15px 20px;
      transition: 0.3s;
    }
    nav a:hover {
      background: #45a29e;
    }

    /* Sections */
    section {
      padding: 50px 20px;
      text-align: center;
    }

    /* Skills Bars */
    .skills-bar {
      background: #333;
      border-radius: 25px;
      margin: 10px auto;
      width: 60%;
      height: 25px;
      overflow: hidden;
    }
    .skills-fill {
      background: linear-gradient(to right, #45a29e, #66fcf1);
      height: 100%;
      width: 0;
      text-align: right;
      padding-right: 10px;
      color: white;
      line-height: 25px;
      transition: width 2s ease;
    }

    /* Footer */
    footer {
      background: #1f2833;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header id="home">
    <h1>Trisha Nabata</h1>
    <p>Exploring the Universe of Web Development 🌌</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>Galactic Explorer</h2>
    <p>Hello! I’m Trisha Nabata, a web developer with a passion for coding, creativity, and exploring the endless universe of possibilities online!</p>
    <img src="https://images.unsplash.com/photo-1529122312420-66f1e37fcd44?auto=format&fit=crop&w=400&q=80" alt="Profile" width="200" style="border-radius: 50%; border: 3px solid #45a29e;">
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>My Cosmic Skills</h2>
    <p>These are my superpowers in web development</p>
    <div class="skills-bar"><div class="skills-fill" data-skill="95%">HTML & CSS</div></div>
    <div class="skills-bar"><div class="skills-fill" data-skill="90%">JavaScript</div></div>
    <div class="skills-bar"><div class="skills-fill" data-skill="85%">React & Web Design</div></div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:nabatatrisha@gmail.com">nabatatrisha@gmail.com</a></p>
    <p>“Let’s explore the digital universe together!”</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Made with 🌌 Universe Spirit</p>
  </footer>

  <script>
    // Animate skill bars on scroll
    window.addEventListener("scroll", function(){
      let skills = document.querySelectorAll(".skills-fill");
      skills.forEach(skill => {
        let rect = skill.getBoundingClientRect();
        if(rect.top < window.innerHeight){
          skill.style.width = skill.getAttribute("data-skill");
        }
      });
    });
  </script>

</body>
</html>
