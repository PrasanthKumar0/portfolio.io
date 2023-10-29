---
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title | default: site.title }}</title>
  <link rel="stylesheet" type="text/css" href="{{ 'css.css' | relative_url }}">
  <link rel="stylesheet" href="{{ 'style.css' | relative_url }}">
  <script src="https://kit.fontawesome.com/66aa7c98b3.js" crossorigin="anonymous"></script>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
</head>
<body>
  <header class="header">
    <nav class="navbar">
      <div class="navbar-container container">
        <div>
          <h1 class="navbar-brand">Prasanth Kumar</h1>
        </div>
        <ul class="menu-items">
          <li><a href="#about">About</a></li>
          <li><a href="#my-works">Portfolio</a></li>
          <li><a href="#contact-me">Contact</a></li>
        </ul>
      </div>
    </nav>
    <div class="home-content" id="home-page">
      <div class="name">
        <h1>Hi, I'm Prasanth Kumar</h1>
        <p>Associate Software Engineer</p>
      </div>
      <div class="angle-down-icon">
        <a href="#about"><i class="fas fa-angle-down"></i></a>
      </div>
    </div>
  </header>
  {{ content }}
  <div class="contact" id="contact-me">
    <div class="container">
      <div class="contact-content">
        <h2>Contact Me</h2>
        <p class="mail">
          Get in touch with me <i class="fas fa-arrow-right"></i> Prasanthkumarakkili@gmail.com
        </p>
        <p class="links">Or find me on:</p>
        <a href="https://www.linkedin.com/in/prasanth-kumar-1a3593289/" target="_blank"><i class="fab fa-linkedin"> Linkedin</i></a>
        <a href="https://github.com/PrasanthKumar0" target="_blank"><i class="fab fa-github"></i> Github</a>
        <a href="https://hashnode.com/@PrasanthA" target="_blank"><i class="fab fa-dev"></i> Hashnode</a>
      </div>
    </div>
  </div>
</body>
</html>
