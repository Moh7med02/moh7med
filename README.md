<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Structural Engineer Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header Section -->
    <header>
        <div class="container">
            <h1>John Doe</h1>
            <p>Structural Engineer | Problem Solver | Innovator</p>
            <a href="#contact" class="btn">Contact Me</a>
        </div>
    </header>
    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome to my portfolio. I am a professional structural engineer with over 5 years of experience in designing and overseeing construction projects. I specialize in the design of residential, commercial, and industrial buildings with a focus on safety, sustainability, and cost-effectiveness.</p>
        </div>
    </section>
    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>Skills & Expertise</h2>
            <ul>
                <li>Structural Design (Reinforced Concrete, Steel, Wood)</li>
                <li>Building Codes and Standards</li>
                <li>AutoCAD & Revit</li>
                <li>Finite Element Analysis (FEA)</li>
                <li>Project Management</li>
                <li>Structural Inspections</li>
            </ul>
        </div>
    </section>
    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project-item">
                <img src="project1.jpg" alt="Project 1">
                <h3>Residential Building Design</h3>
                <p>Designed a modern residential building with a focus on earthquake-resistant structural systems.</p>
            </div>
            <div class="project-item">
                <img src="project2.jpg" alt="Project 2">
                <h3>Commercial Office Complex</h3>
                <p>Led the structural design of a multi-story office complex with sustainable materials and energy-efficient systems.</p>
            </div>
            <div class="project-item">
                <img src="project3.jpg" alt="Project 3">
                <h3>Bridge Design</h3>
                <p>Designed a steel bridge with high durability and low maintenance for heavy traffic load.</p>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="#" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>
    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2025 John Doe | Structural Engineer</p>
        </div>
    </footer>
    <script src="script.js"></script>
</body>
</html>
CSS (style.css)
css
Copy
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}
.container {
    width: 80%;
    margin: 0 auto;
}
header {
    background: #333;
    color: #fff;
    padding: 60px 0;
    text-align: center;
}
header h1 {
    font-size: 3em;
}
header p {
    font-size: 1.2em;
    margin-bottom: 20px;
}
header .btn {
    background: #f39c12;
    padding: 10px 20px;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}
section {
    padding: 40px 0;
}
section h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    text-align: center;
}
ul {
    list-style-type: none;
    padding: 0;
}
ul li {
    font-size: 1.2em;
    margin-bottom: 10px;
}
#projects .project-item {
    display: inline-block;
    width: 30%;
    margin: 10px;
    text-align: center;
}
#projects img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}
#projects h3 {
    margin-top: 10px;
}
#contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
}
#contact form input,
#contact form textarea {
    width: 60%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
}
#contact form button {
    width: 30%;
    background-color: #f39c12;
    padding: 10px 20px;
    border: none;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
