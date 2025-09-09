<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rishabh's GitHub Profile</title>
  <style>
    /* General Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
      color: #333;
    }

    .container {
      max-width: 900px;
      margin: 50px auto;
      background-color: #fff;
      border-radius: 12px;
      padding: 30px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    /* Header */
    .profile-header {
      text-align: center;
    }

    .profile-header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid #4CAF50;
      margin-bottom: 15px;
    }

    .profile-header h1 {
      margin: 0;
      font-size: 2rem;
      color: #4CAF50;
    }

    .profile-header p {
      margin: 5px 0;
      color: #555;
    }

    /* Skills Section */
    .section {
      margin-top: 30px;
    }

    .section h2 {
      color: #4CAF50;
      border-bottom: 2px solid #4CAF50;
      padding-bottom: 5px;
      margin-bottom: 15px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      background-color: #e0f7e9;
      color: #4CAF50;
      padding: 8px 15px;
      border-radius: 20px;
      font-weight: bold;
    }

    /* Projects Section */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .project-card {
      background-color: #f0f0f0;
      padding: 15px;
      border-radius: 12px;
      transition: transform 0.2s;
    }

    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .project-card a {
      text-decoration: none;
      color: #4CAF50;
      font-weight: bold;
    }

    /* Footer */
    .footer {
      text-align: center;
      margin-top: 40px;
      color: #777;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <div class="profile-header">
      <img src="https://via.placeholder.com/150" alt="Profile Picture">
      <h1>Rishabh</h1>
      <p>B.Tech CSE Student | AI & Web Developer | Open Source Enthusiast</p>
    </div>

    <!-- Skills -->
    <div class="section">
      <h2>Skills</h2>
      <div class="skills">
        <span class="skill">Python</span>
        <span class="skill">Java</span>
        <span class="skill">C</span>
        <span class="skill">SQL</span>
        <span class="skill">HTML</span>
        <span class="skill">CSS</span>
        <span class="skill">JavaScript</span>
        <span class="skill">React</span>
      </div>
    </div>

    <!-- Projects -->
    <div class="section">
      <h2>Projects</h2>
      <div class="projects">
        <div class="project-card">
          <a href="#">Portfolio Website</a>
          <p>My personal website showcasing projects and skills.</p>
        </div>
        <div class="project-card">
          <a href="#">AI Chatbot</a>
          <p>Simple AI chatbot built with Python and Flask.</p>
        </div>
        <div class="project-card">
          <a href="#">SQL Practice</a>
          <p>Collection of SQL exercises for learning and practice.</p>
        </div>
      </div>
    </div>

    <!-- Footer -->
    <div class="footer">
      Made with ❤️ by Rishabh
    </div>
  </div>
</body>
</html>
