/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* General layout and background */
body {
  font-family: 'Roboto', sans-serif;
  background-color: #f7f7f7;
  color: #333;
  line-height: 1.6;
  padding: 0;
}

/* Header section */
header {
  background: #2c3e50;
  color: white;
  padding: 20px 0;
  text-align: center;
}

header h1 {
  font-size: 2.5rem;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
}

nav a:hover {
  text-decoration: underline;
}

/* Showcase Section */
.showcase {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  margin: 20px 0;
}

.showcase .project {
  background: white;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  margin: 10px;
  width: 300px;
  text-align: center;
  overflow: hidden;
}

.showcase img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.showcase .project h3 {
  padding: 10px;
  background-color: #ecf0f1;
  font-size: 1.2rem;
}

/* Footer */
footer {
  background: #2c3e50;
  color: white;
  padding: 10px 0;
  text-align: center;
  margin-top: 40px;
}

footer p {
  font-size: 1rem;
}

<section class="showcase">
  <div class="project">
    <img src="path/to/your-image.jpg" alt="Project 1">
    <h3>Project Title</h3>
    <p>Brief description of the project</p>
    <a href="link-to-project" target="_blank">View Project</a>
  </div>
  <!-- Repeat for other projects -->
</section>

.project {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

<header>
  <h1>Gianluca Cersosimo - Power BI Portfolio</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

