<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Trisha Nabata Portfolio</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f0f4f8;
    color: #1e3a8a;
  }

  header {
    background-color: #2563eb;
    color: white;
    text-align: center;
    padding: 50px 20px;
  }

  header img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid white;
    object-fit: cover;
    margin-bottom: 15px;
  }

  header h1 {
    margin: 0;
    font-size: 2em;
  }

  header p {
    margin: 5px 0 0 0;
    font-size: 1.1em;
  }

  nav {
    background-color: #1e40af;
    display: flex;
    justify-content: center;
    padding: 10px 0;
  }

  nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
  }

  nav a:hover {
    text-decoration: underline;
  }

  section {
    padding: 30px 20px;
    max-width: 800px;
    margin: auto;
  }

  h2 {
    border-bottom: 2px solid #2563eb;
    padding-bottom: 5px;
    display: flex;
    align-items: center;
  }

  h2 i {
    margin-right: 10px;
    color: #2563eb;
  }

  ul {
    list-style: none;
    padding: 0;
  }

  li {
    margin: 10px 0;
    font-size: 1em;
  }

  .skills img {
    margin: 5px;
  }

  footer {
    text-align: center;
    padding: 20px;
    background: #e0e7ff;
    margin-top: 30px;
  }

  .contact a {
    color: #2563eb;
    text-decoration: none;
  }

  .contact a:hover {
    text-decoration: underline;
  }
</style>
</head>
<body>

<!-- Header / Home -->
<header>
  <img src="https://avatars.githubusercontent.com/u/12345678?v=4" alt="Profile Picture">
  <h1>👋 Hi, I'm Trisha Nabata</h1>
  <p>19 years old | BSIT Student at SLTCFPDI</p>
</header>

<!-- Navigation -->
<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</nav>

<!-- About Section -->
<section id="about">
  <h2><i class="fas fa-user"></i> About Me</h2>
  <ul>
    <li><i class="fas fa-id-badge"></i> <b>Name:</b> Trisha Nabata</li>
    <li><i class="fas fa-birthday-cake"></i> <b>Age:</b> 19 years old</li>
    <li><i class="fas fa-school"></i> <b>School:</b> SLTCFPDI</li>
    <li><i class="fas fa-home"></i> <b>Address:</b> Salvacion, Pioduran, Albay</li>
    <li><i class="fas fa-phone"></i> <b>Contact No.:</b> 0991 141 8421</li>
    <li><i class="fab fa-facebook"></i> <b>Facebook:</b> <a href="https://www.facebook.com/share/1Bta6YrZfm/" target="_blank">Trisha Nabata</a></li>
  </ul>
</section>

<!-- Skills Section -->
<section id="skills">
  <h2><i class="fas fa-tools"></i> Skills</h2>
  <div class="skills">
    <img src="https://img.shields.io/badge/HTML-HTML?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
    <img src="https://img.shields.io/badge/CSS-CSS?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
    <img src="https://img.shields.io/badge/JavaScript-JavaScript?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  </div>
</section>

<!-- Contact Section -->
<section id="contact">
  <h2><i class="fas fa-envelope"></i> Contact</h2>
  <ul class="contact">
    <li><i class="fas fa-envelope"></i> Email: <a href="mailto:nabatatrisha@gmail.com">nabatatrisha@gmail.com</a></li>
    <li><i class="fas fa-phone"></i> Phone: 0991 141 8421</li>
    <li><i class="fab fa-facebook"></i> Facebook: <a href="https://www.facebook.com/share/1Bta6YrZfm/" target="_blank">Trisha Nabata</a></li>
  </ul>
</section>

<!-- Footer -->
<footer>
  ✨ Learning today, building tomorrow ✨
</footer>

</body>
</html>
