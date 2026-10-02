## Hello! Welcome to my profile! 👋

### 👨‍💻 Programming languages
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

### 🧰 Frameworks and libraries
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)

### 🗄️ Databases and Cloud Hosting
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Skills</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 32px;
      background: #0d1117;
      color: #f0f6fc;
      font-family: Arial, sans-serif;
    }

    h1 {
      margin-bottom: 24px;
      font-size: 34px;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(7, 1fr);
      border: 1px solid #30363d;
      max-width: 1300px;
      margin: auto;
    }

    .skill {
      min-height: 175px;
      padding: 22px 10px;
      border: 1px solid #30363d;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 16px;
      text-align: center;
      animation: appear 0.8s ease both;
      transition: background 0.3s, transform 0.3s;
    }

    .skill:hover {
      background: #161b22;
      transform: translateY(-8px) scale(1.04);
    }

    .skill img {
      width: 76px;
      height: 76px;
      object-fit: contain;
      animation: float 3s ease-in-out infinite;
    }

    .skill span {
      font-size: 20px;
      font-weight: 600;
    }

    .badge {
      width: 76px;
      height: 76px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 16px;
      background: #d32f2f;
      color: white;
      font-weight: bold;
      font-size: 18px;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes appear {
      from {
        opacity: 0;
        transform: scale(0.7) translateY(20px);
      }

      to {
        opacity: 1;
        transform: scale(1) translateY(0);
      }
    }

    @keyframes float {
      0%, 100% {
        transform: translateY(0);
      }

      50% {
        transform: translateY(-7px);
      }
    }

    .skill:nth-child(2) { animation-delay: 0.1s; }
    .skill:nth-child(3) { animation-delay: 0.2s; }
    .skill:nth-child(4) { animation-delay: 0.3s; }
    .skill:nth-child(5) { animation-delay: 0.4s; }
    .skill:nth-child(6) { animation-delay: 0.5s; }
    .skill:nth-child(7) { animation-delay: 0.6s; }
    .skill:nth-child(8) { animation-delay: 0.7s; }
    .skill:nth-child(9) { animation-delay: 0.8s; }
    .skill:nth-child(10) { animation-delay: 0.9s; }

    @media (max-width: 1000px) {
      .skills-grid {
        grid-template-columns: repeat(4, 1fr);
      }
    }

    @media (max-width: 600px) {
      body {
        padding: 12px;
      }

      .skills-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .skill {
        min-height: 145px;
      }
    }
  </style>
</head>

<body>
  <h1>💻 Software and Tools</h1>

  <div class="skills-grid">

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg">
      <span>HTML</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg">
      <span>CSS</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg">
      <span>Bootstrap</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg">
      <span>Tailwind CSS</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg">
      <span>React</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg">
      <span>Next.js</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg">
      <span>JavaScript</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg">
      <span>TypeScript</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg">
      <span>Python</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/express/express-original.svg">
      <span>Express.js</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg">
      <span>Java</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg">
      <span>Spring Boot</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg">
      <span>PHP</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/laravel/laravel-original.svg">
      <span>Laravel</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg">
      <span>React Native</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg">
      <span>Git</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg">
      <span>GitHub</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg">
      <span>MySQL</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg">
      <span>PostgreSQL</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg">
      <span>MongoDB</span>
    </div>

    <div class="skill">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg">
      <span>Docker</span>
    </div>

    <div class="skill">
      <div class="badge">JLPT<br>N2</div>
      <span>Japanese</span>
    </div>

  </div>
</body>
</html>
