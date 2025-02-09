<style>
        /* Adding animations */
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            0% {
                transform: translateX(-100%);
                opacity: 0;
            }
            100% {
                transform: translateX(0);
                opacity: 1;
            }
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }

        /* Apply fadeIn animation to sections */
        h1, h3, p, h2 {
            animation: fadeIn 1.5s ease-in-out;
        }

        /* Apply slideIn effect to images */
        img {
            animation: slideIn 1.5s ease-in-out;
        }

        /* Apply bounce effect to social media links */
        .social-links img {
            transition: transform 0.3s ease;
        }

        .social-links img:hover {
            transform: scale(1.1);
        }

        /* Styling for the tech-stack icons */
        .tech-stack img {
            margin: 10px;
            animation: slideIn 1.5s ease-in-out;
        }

        /* Styling for the overall page layout */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            padding: 20px;
            background-color: #f4f4f4;
        }

        h1, h3, h2 {
            text-align: center;
            color: #333;
        }

        .tech-stack, .social-links {
            text-align: center;
        }

        /* Add some padding around content for better spacing */
        .content {
            padding: 20px;
        }

        /* GitHub stats section */
        .github-stats {
            text-align: center;
            margin: 20px 0;
        }
    </style>


    <h1>Hi 👋, I'm Tek Narayan Yadav</h1>
    <p align="center">
        <img src="https://th.bing.com/th/id/R.201a0fce023b2b6590a6b18a4fdd4f16?rik=i4TmB%2ftPJzQPbg&pid=ImgRaw&r=0" width="400px">
    </p>
    <h3>🚀 Full Stack Web Developer | MERN Stack Enthusiast 🚀</h3>

    <p align="center">
        <img src="https://komarev.com/ghpvc/?username=Siddhartha34y&label=Profile%20views&color=blue&style=flat" alt="Profile Views">
        <img src="https://img.shields.io/github/followers/Siddhartha34y?label=Followers&style=social" alt="GitHub Followers">
    </p>

    <div class="content">
        <h2>🚀 About Me</h2>
        <p>🎓 **Student at KPR Institute of Engineering and Technology**</p>
        <p>🌱 Currently learning **Web Development, DSA with Java & App Development (React Native)**</p>
        <p>🛠 **Building scalable full-stack applications with React.js, Node.js, MongoDB, and Express.js**</p>
        <p>👯 Looking to **collaborate on exciting Web Development projects**</p>
        <p>💬 Ask me about **JavaScript, React, MongoDB, Node.js, Java, Python, and more!**</p>
        <p>🌍 **Check out my Portfolio:** [Click Here](https://imaginative-conkies-077921.netlify.app/)</p>
        <p>⚡ **Fun fact:** I love solving coding challenges & debugging complex issues!</p>

        <h2>🌐 Connect with Me</h2>
        <div class="social-links">
            <a href="mailto:23cs188@kpriet.ac.in"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
            <a href="https://www.linkedin.com/in/tek-narayan-yadav-108938289"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
            <a href="https://www.instagram.com/pawanpawan45677?igsh=bTVsbnRwMndqcThs"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
            <a href="https://www.facebook.com/share/18dQmsKPzp/?mibextid=qi2Omg"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"></a>
        </div>

        <h2>🚀 Tech Stack</h2>
        <h3>🖥️ Programming Languages</h3>
        <div class="tech-stack">
            <img width="48" height="48" src="https://img.icons8.com/color/48/javascript.png" alt="JavaScript"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/java-coffee-cup-logo.png" alt="Java"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/python.png" alt="Python"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/c-programming.png" alt="C"/>
        </div>

        <h3>💻 Frontend</h3>
        <div class="tech-stack">
            <img width="48" height="48" src="https://img.icons8.com/color/48/react-native.png" alt="React.js"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/html-5.png" alt="HTML5"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/css3.png" alt="CSS3"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/bootstrap.png" alt="Bootstrap"/>
        </div>

        <h3>🛠 Backend & Database</h3>
        <div class="tech-stack">
            <img width="48" height="48" src="https://img.icons8.com/color/48/nodejs.png" alt="Node.js"/>
            <img width="48" height="48" src="https://img.icons8.com/?size=100&id=2ZOaTclOqD4q&format=png&color=000000" alt="Express.js"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/mongodb.png" alt="MongoDB"/>
        </div>

        <h3>🛠 Tools & IDEs</h3>
        <div class="tech-stack">
            <img width="48" height="48" src="https://img.icons8.com/color/48/visual-studio-code-2019.png" alt="VS Code"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/intellij-idea.png" alt="IntelliJ IDEA"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/android-studio--v2.png" alt="Android Studio"/>
            <img width="48" height="48" src="https://img.icons8.com/color/48/git.png" alt="Git"/>
        </div>

        <h2>📊 GitHub Stats</h2>
        <div class="github-stats">
            <img src="https://github-readme-stats.vercel.app/api?username=Siddhartha34y&show_icons=true&theme=tokyonight" alt="GitHub Stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=Siddhartha34y&theme=dark" alt="GitHub Streak">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Siddhartha34y&layout=compact&theme=radical" alt="Top Languages">
        </div>

        <h2>🎯 Fun Projects</h2>
        <div>
            <h3>🌟 Explorer's Hub</h3>
            <p>A travel guide website that provides detailed information about **Paris, NYC, Tokyo**, and more!</p>
            <p>**Tech Stack:** HTML, CSS, JavaScript</p>
            <a href="https://your-project-link.com">📽 Live Demo</a>
        </div>

        <div>
            <h3>🌟 Spotify WebSite (Frontend)</h3>
            <p>A responsive UI clone of Spotify Web with interactive Listing Song features.</p>
            <p>**Tech Stack:** HTML, CSS, JavaScript, TailwindCSS</p>
            <a href="https://github.com/Siddhartha34y/Siddhartha34y/blob/main/WhatsApp%20Video%202025-02-10%20at%2001.23.17_fb472fe5.mp4">📽 Live Demo</a>
        </div>

        <div>
            <h3>🌟 Twitter Clone</h3>
            <p>A frontend clone of Twitter using Tailwind CSS.</p>
            <p>**Tech Stack:** HTML, Tailwind CSS</p>
            <a href="https://github.com/Siddhartha34y/Siddhartha34y/commit/f07734399f139418c6eceda06fac40df71dd36c1">📽 Live Demo</a>
        </div>

        <h2>🎯 My Goals for 2025</h2>
        <ul>
            <li>✅ Master **React & MERN Stack**</li>
            <li>✅ Improve **Data Structures & Algorithms (DSA)**</li>
            <li>✅ Build **Full-Stack Projects & APIs**</li>
            <li>✅ Contribute to **Open Source**</li>
            <li>✅ Develop **React Native Mobile Apps**</li>
        </ul>

        <h2>🚀 Thank you for visiting!</h2>
        <p>Don't forget to **star ⭐ my repositories** and follow for more updates.</p>
    </div>

    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Siddhartha34y/Siddhartha34y/output/github-snake-dark.svg" />
        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Siddhartha34y/Siddhartha34y/output/github-snake.svg" />
        <img alt="github-snake" src="https://raw.githubusercontent.com/Siddhartha34y/Siddhartha34y/output/github-snake.svg" />
    </picture>
