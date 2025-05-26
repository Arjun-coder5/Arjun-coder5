<!-- Advanced Animated Neon README -->

<h1 align="center" style="font-family: 'Fira Code', monospace; font-weight: 900; font-size: 3rem; letter-spacing: 3px; color:#00FFAA; 
   -webkit-text-stroke: 1.5px #00FFAA; text-shadow:
      0 0 5px #00FFAA,
      0 0 10px #00FFAA,
      0 0 20px #00FFAA,
      0 0 40px #00FFAA,
      0 0 80px #00FFAA;">
  <span id="typing"></span>
  <span class="cursor">|</span>
</h1>

<style>
  /* Typing Effect */
  #typing {
    display: inline-block;
    white-space: nowrap;
    overflow: hidden;
    border-right: 0.15em solid #00ffaa;
    animation:
      typing 4s steps(30, end) infinite,
      blink-caret 0.75s step-end infinite;
  }

  .cursor {
    animation: blink-caret 0.75s step-end infinite;
  }

  @keyframes typing {
    0% { width: 0 }
    50% { width: 24ch; }
    100% { width: 0 }
  }

  @keyframes blink-caret {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }

  /* Neon Glow Hover for badges */
  .badge-glow:hover {
    filter: drop-shadow(0 0 6px #00ffaa) drop-shadow(0 0 10px #00ffaa);
    transition: 0.3s ease-in-out;
  }

  /* Gradient Section Titles */
  .gradient-title {
    background: linear-gradient(90deg, #00ff99, #00ccff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: 800;
    font-size: 2.5rem;
    margin: 2rem 0 1rem 0;
    text-align: center;
    text-shadow:
      0 0 10px #00ff99,
      0 0 20px #00ccff;
  }

  /* Neon Button */
  .neon-btn {
    color: #00ffaa;
    background: transparent;
    border: 2px solid #00ffaa;
    border-radius: 50px;
    padding: 0.5em 1.5em;
    font-weight: 700;
    cursor: pointer;
    box-shadow:
      0 0 10px #00ffaa,
      0 0 20px #00ffaa,
      0 0 40px #00ffaa;
    animation: neon-flicker 3s infinite;
    text-decoration: none;
    display: inline-block;
    margin: 0.5rem;
    transition: 0.2s ease-in-out;
  }

  .neon-btn:hover {
    box-shadow:
      0 0 20px #00ffaa,
      0 0 40px #00ffaa,
      0 0 80px #00ffaa;
    transform: scale(1.05);
  }

  @keyframes neon-flicker {
    0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% {
      opacity: 1;
      text-shadow:
        0 0 10px #00ffaa,
        0 0 20px #00ffaa,
        0 0 40px #00ffaa;
    }
    20%, 22%, 24%, 55% {
      opacity: 0.8;
      text-shadow: none;
    }
  }
</style>

---

<h2 class="gradient-title">About Me</h2>
<p align="center" style="color:#00ffaa; max-width:700px; font-size:1.1rem;">
  🎓 B.Tech Computer Science | Passionate about <b>DSA</b> & <b>Full-Stack MERN Development</b><br>
  🚀 Committed to solving real-world problems with clean, scalable code.<br>
  🌱 Active open-source contributor and lifelong learner.<br>
  🎯 Aiming for software engineering roles at Google & Microsoft.
</p>

---

<h2 class="gradient-title">Tech Stack</h2>
<p align="center">
  <img class="badge-glow" src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img class="badge-glow" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img class="badge-glow" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img class="badge-glow" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img class="badge-glow" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img class="badge-glow" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img class="badge-glow" src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code" />
</p>

---

<h2 class="gradient-title">GitHub Stats</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Arjun-coder5&show_icons=true&theme=radical&count_private=true&hide_title=true" alt="GitHub Stats" />
</p>

---

<h2 class="gradient-title">Projects</h2>
<ul style="max-width:700px; margin:auto; color:#00ffaa; font-size:1.1rem; line-height:1.6;">
  <li><b><a href="https://github.com/Arjun-coder5/Daily-DSA" target="_blank" style="color:#00ccff; text-decoration:none;" onmouseover="this.style.textDecoration='underline'" onmouseout="this.style.textDecoration='none'">Daily-DSA</a></b> – Daily grind of solving complex DSA problems on LeetCode, Codeforces, GFG.</li>
  <li><b><a href="https://github.com/Arjun-coder5/Open-Source-Contributions" target="_blank" style="color:#00ccff; text-decoration:none;" onmouseover="this.style.textDecoration='underline'" onmouseout="this.style.textDecoration='none'">Open-Source-Contributions</a></b> – Contributing bug fixes & features to impactful OSS projects.</li>
  <li><b><a href="https://github.com/Arjun-coder5/System-Design" target="_blank" style="color:#00ccff; text-decoration:none;" onmouseover="this.style.textDecoration='underline'" onmouseout="this.style.textDecoration='none'">System-Design</a></b> – Designing scalable & fault-tolerant system architectures.</li>
  <li><b><a href="https://github.com/Arjun-coder5/Web-Dev" target="_blank" style="color:#00ccff; text-decoration:none;" onmouseover="this.style.textDecoration='underline'" onmouseout="this.style.textDecoration='none'">Web-Dev</a></b> – Frontend projects with sleek UI/UX designs & modern web tech.</li>
</ul>

---

<h2 class="gradient-title">Let's Connect</h2>
<p align="center">
  <a href="mailto:arjunsorout526@gmail.com" class="neon-btn" target="_blank" rel="noopener noreferrer">Email Me</a>
  <a href="https://linkedin.com/in/arjun-sorout-9aa10a290" class="neon-btn" target="_blank" rel="noopener noreferrer">LinkedIn</a>
  <a href="https://github.com/Arjun-coder5" class
