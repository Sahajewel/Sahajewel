<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Banner</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .banner {
            width: 1000px;
            height: 300px;
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 50%, #667eea 100%);
            border-radius: 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
            overflow: hidden;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }

        .banner::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 1px, transparent 1px);
            background-size: 50px 50px;
            animation: float 20s infinite linear;
        }

        @keyframes float {
            0% { transform: translate(0, 0) rotate(0deg); }
            100% { transform: translate(-50px, -50px) rotate(360deg); }
        }

        .content {
            text-align: center;
            z-index: 2;
        }

        .name {
            font-size: 3.5rem;
            font-weight: 700;
            color: white;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            letter-spacing: 2px;
        }

        .title {
            font-size: 1.5rem;
            color: rgba(255,255,255,0.9);
            margin: 10px 0 30px 0;
            font-weight: 300;
            letter-spacing: 1px;
        }

        .tech-stack {
            display: flex;
            gap: 20px;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
        }

        .tech-logo {
            width: 45px;
            height: 45px;
            background: rgba(255,255,255,0.1);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            font-weight: bold;
            color: white;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
            transition: all 0.3s ease;
            position: relative;
        }

        .tech-logo:hover {
            transform: translateY(-5px);
            background: rgba(255,255,255,0.2);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }

        .js { color: #f7df1e; }
        .ts { color: #3178c6; }
        .react { color: #61dafb; }
        .node { color: #68a063; }
        .express { color: #fff; }
        .mongo { color: #4db33d; }
        .mongoose { color: #880000; }
        .postgres { color: #336791; }

        .decoration {
            position: absolute;
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: rgba(255,255,255,0.05);
        }

        .decoration-1 {
            top: -30px;
            right: -30px;
        }

        .decoration-2 {
            bottom: -30px;
            left: -30px;
        }
    </style>
</head>
<body>
    <div class="banner">
        <div class="decoration decoration-1"></div>
        <div class="decoration decoration-2"></div>
        
        <div class="content">
            <h1 class="name">Saha Jewel Kumar</h1>
            <p class="title">Fullstack Developer</p>
            
            <div class="tech-stack">
                <div class="tech-logo js" title="JavaScript">JS</div>
                <div class="tech-logo ts" title="TypeScript">TS</div>
                <div class="tech-logo react" title="React">⚛</div>
                <div class="tech-logo node" title="Node.js">N</div>
                <div class="tech-logo express" title="Express">E</div>
                <div class="tech-logo mongo" title="MongoDB">M</div>
                <div class="tech-logo mongoose" title="Mongoose">🍃</div>
                <div class="tech-logo postgres" title="PostgreSQL">🐘</div>
            </div>
        </div>
    </div>
</body>
</html>


<h1 align="center">Hi, I'm Saha Jewel Kumar 👋</h1>
<p align="center">
  <strong>Full Stack Developer (MERN Stack)</strong> <br />
  Crafting clean, scalable, and modern web applications
</p>

---

## 🧠 About Me

- 🔁 Transitioned from Civil Engineering to Web Development
- 💻 Skilled in building full stack applications using the MERN stack
- 🌐 Based in 🇯🇵 Japan, originally from 🇧🇩 Bangladesh
- 🌱 Currently focused on TypeScript, Clean Code, and Backend Architecture
- 🤝 Open to new opportunities in full stack or frontend roles
- 🗣️ Fluent in Japanese & English
- 📞 Contact: +81 80 5052 6822

---

## 🚀 Tech Stack

<div align="center">

<!-- Frontend -->
<img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=for-the-badge" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Redux-764ABC?logo=redux&logoColor=white&style=for-the-badge" />

<!-- Backend -->
<br />
<img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Mongoose-880000?logo=mongoose&logoColor=white&style=for-the-badge" />

<!-- Tools -->
<br />
<img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge" />


</div>

---

## 🌐 Connect with Me

<div align="center">
  <a href="https://www.linkedin.com/in/sahajewelkumar/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge" />
  </a>
  <a href="https://x.com/sahaJewelkumar" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white&style=for-the-badge" />
  </a>
</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sahajewel&show_icons=true&theme=radical&count_private=true&hide_border=false" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sahajewel&layout=compact&theme=radical&hide_border=false" height="150" />
</div>

---

<p align="center">
  🔥 "Code with purpose. Learn with passion. Build for impact." 💡
</p>
