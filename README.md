<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PraBhaT_PraJaPaTi</title>
  <style>
    body {
      background-color: #0a192f;
      color: #ccd6f6;
      font-family: Arial, sans-serif;
      text-align: center;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
    }
    .container {
      position: relative;
      width: 100%;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }
    .animated-text {
      font-size: 60px;
      font-weight: bold;
      color: #64ffda;
      text-shadow: 0px 0px 20px #64ffda;
      opacity: 0;
      animation: fadeInOut 3s infinite alternate;
    }
    @keyframes fadeInOut {
      0% { opacity: 0; transform: scale(0.8); }
      50% { opacity: 1; transform: scale(1.2); }
      100% { opacity: 0; transform: scale(0.8); }
    }
    .glow {
      font-size: 24px;
      color: #64ffda;
      text-shadow: 0px 0px 10px #64ffda;
      animation: glow 2s infinite alternate;
    }
    @keyframes glow {
      from { opacity: 1; }
      to { opacity: 0.5; }
    }
    .section {
      max-width: 800px;
      margin: 40px auto;
      text-align: left;
      padding: 20px;
      line-height: 1.8;
    }
    h2 {
      color: #64ffda;
      margin-bottom: 10px;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li::before {
      content: "✔️ ";
      color: #64ffda;
    }
    .quote {
      text-align: center;
      font-size: 20px;
      margin-top: 40px;
      color: #64ffda;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="animated-text">Hey there, I'm PraBhaT_PraJaPaTi 👋</h1>
    <p class="glow">🚀 Full Stack Developer | 💻 Java Enthusiast | ❤️ Lifelong Learner</p>
  </div>

  <div class="section">
    <h2>🧑‍💻 About Me</h2>
    <ul>
      <li>Experienced Java Full Stack Developer</li>
      <li>Passionate about building scalable web applications</li>
      <li>Always ready to help and collaborate on exciting projects</li>
      <li>Continuously learning new tech trends</li>
    </ul>
  </div>

  <div class="section">
    <h2>🚀 Tech Stack</h2>
    <p><b>Programming Languages:</b> Java, Python, JavaScript</p>
    <p><b>Frontend Frameworks:</b> React, Vite, Tailwind CSS</p>
    <p><b>Backend:</b> Spring Framework, Spring Boot, Spring JDBC, Microservices</p>
    <p><b>Database:</b> MySQL, MongoDB, PostgreSQL</p>
    <p><b>Cloud & Hosting:</b> AWS, Firebase, Vercel</p>
  </div>

  <div class="section" style="text-align:center;">
    <h2>🌐 Connect with Me</h2>
    <p>LinkedIn: linkedin.com/in/prabhat-prajapati-01p6</p>
    <p>Email: prabhatprajapti01@gmail.com</p>
  </div>

  <p class="quote">⭐ "Code more, worry less!" 🚀</p>
</body>
</html>
