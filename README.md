<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Course Website</title>
  <style>
    body {font-family: Arial; margin: 0; background: #f4f4f4;}
    header {background: #333; color: white; padding: 15px; text-align: center;}
    nav {background: #555; padding: 10px; text-align: center;}
    nav a {color: white; margin: 10px; text-decoration: none;}
    .hero {padding: 50px; text-align: center; background: #fff;}
    .courses {display: flex; justify-content: center; gap: 20px; padding: 20px;}
    .card {background: white; padding: 20px; border-radius: 10px; width: 250px; box-shadow: 0 0 10px rgba(0,0,0,0.1);}
    button {background: #28a745; color: white; border: none; padding: 10px; cursor: pointer;}
    footer {background: #333; color: white; text-align: center; padding: 10px;}
  </style>
</head>
<body><header>
  <h1>My Online Course</h1>
  <p>Learn Skills. Grow Fast.</p>
</header><nav>
  <a href="#">Home</a>
  <a href="#courses">Courses</a>
  <a href="#contact">Contact</a>
</nav><section class="hero">
  <h2>Start Learning Today</h2>
  <p>Join our courses and upgrade your skills.</p>
  <button onclick="alert('Enroll feature coming soon!')">Enroll Now</button>
</section><section id="courses" class="courses">
  <div class="card">
    <h3>Web Development</h3>
    <p>Learn HTML, CSS, JavaScript</p>
    <button>View Course</button>
  </div>
  <div class="card">
    <h3>Fitness Training</h3>
    <p>Build body and stay fit</p>
    <button>View Course</button>
  </div>
</section><section id="contact" class="hero">
  <h2>Contact Us</h2>
  <p>Email: your@email.com</p>
</section><footer>
  <p>© 2026 My Course Website</p>
</footer></body>
</html>
