# dmahjoob.github.io

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - GitHub.io</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <!-- Navigation Section -->
  <header>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#funfacts">Fun Facts</a></li>
        <li><a href="#interests">Interests</a></li>
      </ul>
    </nav>
  </header>

  <!-- About Me Section -->
  <section id="about">
    <h1>About Me</h1>
    <p>Hello! I'm Darius Mahjoob, a Computer Science & Business Administration major at USC. I have a passion for AI, digital marketing, and jazz music. Welcome to my personal website!</p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h1>Projects</h1>
    <ul>
      <li>Project 1 - Description</li>
      <li>Project 2 - Description</li>
      <li>Project 3 - Description</li>
    </ul>
  </section>

  <!-- Fun Facts Section -->
  <section id="funfacts">
    <h1>Fun Facts</h1>
    <ul>
      <li>I can play the saxophone 🎷</li>
      <li>I love exploring digital marketing strategies 🚀</li>
      <li>My favorite book is <strong>Thinking, Fast and Slow</strong> 📚</li>
    </ul>
  </section>

  <!-- Interests Section -->
  <section id="interests">
    <h1>Interests</h1>
    <p>I enjoy learning about technology trends, exploring jazz improvisation, and collaborating with creative thinkers to solve problems in unique ways. Let’s connect and create something amazing!</p>
  </section>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2024 Darius Mahjoob</p>
  </footer>
  <!-- Link JavaScript if needed -->
  <script src="script.js"></script>
</body>

</html>

/* Reset some default browser styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* General body styles */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background: #f5f5f5;
}

/* Header navigation styles */
header {
  background: #333;
  color: #fff;
  padding: 10px 0;
  text-align: center;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #f39c12;
}

/* Section Styling */
section {
  padding: 20px;
  margin: 10px auto;
  max-width: 800px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  background: #fff;
}

section h1 {
  margin-bottom: 10px;
  font-size: 24px;
  color: #333;
}

/* Footer Styling */
footer {
  text-align: center;
  padding: 10px 0;
  background: #333;
  color: #fff;
  font-size: 14px;
  margin-top: 20px;
}

/* Responsive Design */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  nav ul li {
    margin: 5px 0;
  }

  section {
    padding: 15px;
  }
}
