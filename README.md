<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PraBhaT PraJaPaTi</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-br from-[#0a192f] to-[#020c1b] text-[#ccd6f6] font-sans">

  <!-- Navbar -->
  <nav class="fixed w-full top-0 bg-[#0a192f]/80 backdrop-blur-md z-50 shadow-md">
    <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-[#64ffda]">Prabhat</h1>
      <div class="space-x-6 text-lg hidden md:flex">
        <a href="#about" class="hover:text-[#64ffda] transition">About</a>
        <a href="#tech" class="hover:text-[#64ffda] transition">Tech Stack</a>
        <a href="#connect" class="hover:text-[#64ffda] transition">Connect</a>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="flex flex-col justify-center items-center text-center h-screen px-4">
    <h1 class="text-5xl md:text-7xl font-extrabold text-[#64ffda] animate-pulse drop-shadow-[0_0_25px_rgba(100,255,218,0.7)] leading-tight">
      Hey there, I'm <span class="text-white">PraBhaT PraJaPaTi</span> 👋
    </h1>
    <p class="mt-4 text-xl md:text-2xl text-[#64ffda]">
      🚀 Full Stack Developer | 💻 Java Expert | ❤️ Lifelong Learner
    </p>
    <button class="mt-8 px-6 py-3 text-lg font-semibold bg-[#64ffda] text-[#0a192f] rounded-xl shadow-lg hover:bg-[#52e6c1] transition duration-300">
      View My Work
    </button>
  </section>

  <!-- About Me Section -->
  <section id="about" class="max-w-4xl mx-auto my-20 p-8 bg-[#112240] border-l-4 border-[#64ffda] rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <h2 class="text-3xl text-[#64ffda] mb-6 font-bold">🧑‍💻 About Me</h2>
    <ul class="space-y-3 text-lg leading-relaxed">
      <li>✔️ Java Full Stack Developer with 3+ years of real-world experience</li>
      <li>✔️ Passionate about creating scalable, efficient, and secure web applications</li>
      <li>✔️ Proficient in Java, React, Spring Boot, REST APIs, and system design</li>
      <li>✔️ Strong team player who loves collaborating and mentoring others</li>
      <li>✔️ Highly focused on clean code, performance, and maintainability</li>
      <li>✔️ Always exploring new technologies and development patterns</li>
    </ul>
    <p class="mt-6 text-[#64ffda] italic text-lg text-center">
      💡 "Code should be simple, readable, and powerful."
    </p>
  </section>

  <!-- Tech Stack Section -->
  <section id="tech" class="max-w-4xl mx-auto my-20 p-8 bg-[#112240] border-l-4 border-[#64ffda] rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <h2 class="text-3xl text-[#64ffda] mb-6 font-bold">🚀 Tech Stack</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-lg">
      <p><b>Programming Languages:</b> Java, Python, JavaScript</p>
      <p><b>Frontend:</b> React, Vite, Tailwind CSS</p>
      <p><b>Backend:</b> Spring Boot, Spring Security, Microservices, JDBC</p>
      <p><b>Database:</b> MySQL, MongoDB, PostgreSQL</p>
      <p><b>Cloud:</b> AWS, Firebase</p>
      <p><b>Deployment:</b> Vercel, Render</p>
    </div>
  </section>

  <!-- Connect Section -->
  <section id="connect" class="max-w-4xl mx-auto my-20 p-8 text-center bg-[#112240] border-l-4 border-[#64ffda] rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <h2 class="text-3xl text-[#64ffda] mb-6 font-bold">🌐 Connect with Me</h2>
    <p class="text-xl mb-2">LinkedIn:<br> <span class="text-[#64ffda]">linkedin.com/in/prabhat-prajapati-01p6</span></p>
    <p class="text-xl mb-2">Email:<br> <span class="text-[#64ffda]">prabhatprajapti01@gmail.com</span></p>
  </section>

  <!-- Quote -->
  <p class="text-center text-[#64ffda] text-2xl italic my-16">
    ⭐ "Code more, worry less!" 🚀
  </p>

</body>
</html>
