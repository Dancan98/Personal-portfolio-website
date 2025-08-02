<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>My Portfolio | Dancan Mulupi</title>
  <style>
    /* Reset & base */
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: #f9fafb;
      color: #333;
      line-height: 1.6;
    }
    a {
      color: #2a9d8f;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #21867a;
    }
    h1, h2, h3 {
      margin-bottom: 0.5rem;
      color: #264653;
    }
    p {
      margin-top: 0;
    }

    /* Container */
    .container {
      max-width: 900px;
      margin: 2rem auto 4rem;
      background: white;
      padding: 2rem 3rem;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }

    /* Header */
    header {
      background-color: #2a9d8f;
      color: white;
      padding: 2.25rem 1rem;
      text-align: center;
      box-shadow: 0 3px 10px rgba(0,0,0,0.15);
    }
    header h1 {
      font-size: 2.8rem;
      margin: 0;
      font-weight: 700;
      letter-spacing: 1.3px;
    }
    header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
      font-weight: 300;
    }

    /* Section styling */
    section {
      margin-bottom: 2.5rem;
    }
    section h2 {
      border-left: 6px solid #2a9d8f;
      padding-left: 0.9rem;
      font-weight: 700;
      font-size: 1.9rem;
      margin-bottom: 1rem;
    }

    /* Programming languages list */
    ul.skills-list {
      list-style: none;
      padding-left: 0;
      display: flex;
      flex-wrap: wrap;
      gap: 1rem 1.5rem;
    }
    ul.skills-list li {
      background-color: #e0f7f1;
      padding: 0.5rem 1rem;
      border-radius: 20px;
      font-weight: 600;
      color: #2a9d8f;
      box-shadow: 0 2px 6px rgba(42,157,143,0.3);
    }

    /* Education */
    .education p {
      margin-bottom: 0.6rem;
      font-size: 1.1rem;
    }
    .cv-link {
      display: inline-block;
      background-color: #2a9d8f;
      color: white;
      padding: 0.5rem 1.2rem;
      border-radius: 5px;
      font-weight: 600;
      margin-top: 0.6rem;
      box-shadow: 0 3px 8px rgba(42,157,143,0.6);
      transition: background-color 0.3s ease;
    }
    .cv-link:hover {
      background-color: #21867a;
    }

    /* Interests */
    ul.interests-list {
      list-style: disc inside;
      font-size: 1.1rem;
      line-height: 1.6;
    }

    /* Projects */
    ul.projects-list {
      list-style: none;
      padding-left: 0;
    }
    ul.projects-list li {
      margin-bottom: 1.1rem;
    }
    ul.projects-list li a {
      font-weight: 600;
      font-size: 1.1rem;
    }
    ul.projects-list li p {
      margin: 0.2rem 0 0 0;
      color: #555;
      font-style: italic;
      font-size: 0.95rem;
    }

    /* Contact Form */
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
    }
    label {
      font-weight: 600;
      margin-bottom: 0.3rem;
    }
    input[type="text"],
    input[type="email"],
    textarea {
      padding: 0.6rem 0.8rem;
      border-radius: 6px;
      border: 1.8px solid #ccc;
      font-size: 1rem;
      transition: border-color 0.3s ease;
      resize: vertical;
      font-family: inherit;
    }
    input[type="text"]:focus,
    input[type="email"]:focus,
    textarea:focus {
      border-color: #2a9d8f;
      outline: none;
    }
    textarea {
      min-height: 120px;
    }
    button[type="submit"] {
      background-color: #2a9d8f;
      color: white;
      border: none;
      padding: 0.75rem;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 700;
      font-size: 1.1rem;
      max-width: 150px;
      transition: background-color 0.3s ease;
    }
    button[type="submit"]:hover {
      background-color: #21867a;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 1.5rem 1rem;
      background: #264653;
      color: white;
      font-size: 0.9rem;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .container {
        margin: 1rem;
        padding: 1.5rem 1.8rem;
      }
      header h1 {
        font-size: 2rem;
      }
      section h2 {
        font-size: 1.5rem;
      }
      ul.skills-list {
        justify-content: center;
      }
      form {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Dancan Mulupi</h1>
  <p>Passionate Web Developer | Tech Enthusiast | Problem Solver</p>
</header>

<div class="container">

  <section id="programming-languages">
    <h2>Programming Languages</h2>
    <ul class="skills-list">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript</li>
      <li>Python</li>
      <li>Java</li>
    </ul>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I’m <strong>Dancan Mulupi</strong>, a dedicated web developer with a passion for creating clean, functional, and engaging web experiences. I thrive on problem solving and continuously learning new technologies to build better solutions that make a difference.</p>
  </section>

  <section id="education" class="education">
    <h2>Educational Background</h2>
    <p><strong>Bachelor of Economics and Statistics</strong></p>
    <p>University of Nairobi, 2021</p>
    <a href="MULUPI/DANCAN MULUPI_CV.pdf" download="DANCAN MULUPI_CV.pdf" class="cv-link" aria-label="Download My CV">Download My CV</a>
  </section>

  <section id="interests">
    <h2>Interests</h2>
    <ul class="interests-list">
      <li>Web Development: Exploring modern frameworks and best practices.</li>
      <li>Tech Innovations: Keeping up with trending technologies and AI.</li>
      <li>Open Source: Contributing to projects that empower communities.</li>
      <li>Environmental Tech: Using technology for sustainability.</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul class="projects-list">
      <li>
        <a href="https://github.com/Dancan98/project1" target="_blank" rel="noopener noreferrer">GreenHome IoT Dashboard</a>
        <p>A real-time greenhouse monitoring system using IoT sensors and data visualization.</p>
      </li>
      <li>
        <a href="https://github.com/Dancan98/project2" target="_blank" rel="noopener noreferrer">Personal Portfolio Site</a>
        <p>Responsive personal portfolio showcasing projects, skills, and contact form built from scratch.</p>
      </li>
      <li>
        <a href="https://github.com/Dancan98/project3" target="_blank" rel="noopener noreferrer">Weather-Now App</a>
        <p>A web app that fetches and displays real-time weather and climate data using open APIs.</p>
      </li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form action="mailto:your.email@example.com" method="POST" enctype="text/plain" target="_blank" novalidate>
      <label for="name">Name:</label>
      <input type="text" id="name" name="Name" required placeholder="Your name" />

      <label for="email">Email:</label>
      <input type="email" id="email" name="Email" required placeholder="your.email@example.com" />

      <label for="message">Message:</label>
      <textarea id="message" name="Message" required placeholder="Write your message here..."></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>
  
</div>

<footer>
  &copy; 2025 Dancan Mulupi. All rights reserved.
</footer>

</body>
</html>
