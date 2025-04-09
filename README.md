# Project-1
project without help of java script and backend
*****************HTML Code*******************
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GDG - JSS University</title>
  <link rel="stylesheet" href="style4.css" />
</head>
<body>
  <header>
    <h1>GDG - JSS University</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="events.html">Events</a>
      <a href="team.html">Team</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Code. Connect. Collaborate.</h2>
    <p>Welcome to GDG Club of JSS University — A Place for Tech Lovers!</p>
  </section>

  <footer>
    <p>&copy; 2025 GDG Club, JSS University</p>
  </footer>
</body>
</html>

**********************CSS Code*******************
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #f4f7fa;
    color: #222;
  }
  
  header {
    background-color: #4285F4;
    color: white;
    padding: 20px;
    text-align: center;
  }
  
  nav {
    margin-top: 10px;
  }
  
  nav a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
    font-weight: bold;
  }
  
  nav a:hover {
    color: #ffcc00;
  }
  
  .hero {
    padding: 100px 20px;
    background: linear-gradient(to right, #34a853, #4285f4);
    text-align: center;
    color: white;
  }
  
  footer {
    background-color: #202124;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 50px;
  }
  
