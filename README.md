<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Website</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f7fb;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #0f172a;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #1e293b;
      padding: 10px;
      text-align: center;
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

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      margin: 15px 0;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    footer {
      background: #0f172a;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    button {
      padding: 10px 20px;
      background: #2563eb;
      border: none;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background: #1d4ed8;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Website</h1>
    <p>This website is hosted on GitHub Pages 🚀</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">

    <section id="home" class="card">
      <h2>Home</h2>
      <p>This is my first GitHub website. I created it using HTML, CSS and JavaScript.</p>
      <button onclick="alert('Hello! Welcome to my website 😊')">Click Me</button>
    </section>

    <section id="about" class="card">
      <h2>About Me</h2>
      <p>
        Hi! I am a web learner and this is my personal website. 
        I am learning GitHub, web development, and technology.
      </p>
    </section>

    <section id="services" class="card">
      <h2>My Services</h2>
      <ul>
        <li>🌐 Website Design</li>
        <li>💻 Basic Web Development</li>
        <li>📊 Excel & Office Support</li>
      </ul>
    </section>

    <section id="contact" class="card">
      <h2>Contact</h2>
      <p>Email: yourname@gmail.com</p>
      <p>GitHub: https://github.com/yourusername</p>
    </section>

  </div>

  <footer>
    <p>© 2026 My Website | Powered by GitHub Pages</p>
  </footer>

</body>
</html>
