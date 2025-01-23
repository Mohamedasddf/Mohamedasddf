<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Hesham's Portfolio</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }

        h1, h3, p, .skills-container {
            text-align: center;
        }

        /* Skill container */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }

        .skill-item {
            text-align: center;
            font-size: 40px;
            padding: 20px;
            border-radius: 10px;
            background-color: #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, opacity 0.3s ease;
            opacity: 0;
            transform: translateY(50px);
            animation: fadeInUp 1s ease-out forwards;
        }

        /* Delay each skill item */
        .skill-item:nth-child(1) {
            animation-delay: 0.2s;
        }

        .skill-item:nth-child(2) {
            animation-delay: 0.4s;
        }

        .skill-item:nth-child(3) {
            animation-delay: 0.6s;
        }

        .skill-item:nth-child(4) {
            animation-delay: 0.8s;
        }

        .skill-item:nth-child(5) {
            animation-delay: 1s;
        }

        .skill-item:nth-child(6) {
            animation-delay: 1.2s;
        }

        .skill-item:nth-child(7) {
            animation-delay: 1.4s;
        }

        /* Keyframe Animation */
        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Skill icon hover effect */
        .skill-item:hover {
            transform: scale(1.1);
            opacity: 0.8;
        }

        .badge {
            display: inline-block;
            padding: 10px 20px;
            border-radius: 10px;
            color: #fff;
            margin: 10px;
            font-size: 18px;
        }
        
        .badge.python { background-color: #3776AB; }
        .badge.django { background-color: #092E20; }
        .badge.postgresql { background-color: #316192; }
        .badge.html { background-color: #E34F26; }
        .badge.css { background-color: #1572B6; }
        .badge.git { background-color: #F05032; }
        .badge.github { background-color: #181717; }
        .badge.postman { background-color: #FF6C37; }

        /* Links */
        a {
            color: #0366d6;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>
    <h1 align="center">Hi there 👋, I'm Mohamed Hesham</h1>
    <h3 align="center">Ambitious Backend Developer | Computer Science Student</h3>

    <p align="center">
        📍 <strong>Location:</strong> Tanta, Gharbia, Egypt <br>
        📧 <strong>Email:</strong> <a href="mailto:mh1351448@gmail.com">mh1351448@gmail.com</a> <br>
        📞 <strong>Phone:</strong> 01013932585 <br>
        🌐 <strong>Portfolio:</strong> <a href="https://mohamedasddf.github.io/portfolio/">My Portfolio</a> <br>
        🐙 <strong>GitHub:</strong> <a href="https://github.com/Mohamedasddf">My GitHub</a> <br>
        🔗 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/mohamed-hesham-89800029b/">My LinkedIn</a>
    </p>

    <hr>

    <h3>🌟 About Me</h3>
    <p>
        I am an **ambitious Backend Developer** and a **Computer Science student** with a proven track record in designing and implementing scalable backend systems. My expertise includes:
    </p>
    <ul>
        <li><strong>Proficient in:</strong> Python, Django, PostgreSQL, and SQL.</li>
        <li><strong>Experience in:</strong> Developing RESTful APIs, integrating secure authentication methods (JWT, Token Authentication), and utilizing modern development tools like GitHub, Git, and Postman.</li>
        <li>Committed to **continuous learning**, **problem-solving**, and delivering **high-quality, efficient solutions**.</li>
    </ul>

    <hr>

    <h3>💻 Technical Skills</h3>
    <div class="skills-container">
        <div class="skill-item">
            <i class="fab fa-python"></i>
            <p>Python</p>
        </div>
        <div class="skill-item">
            <i class="fab fa-django"></i>
            <p>Django</p>
        </div>
        <div class="skill-item">
            <i class="fas fa-database"></i>
            <p>PostgreSQL</p>
        </div>
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <p>HTML5</p>
        </div>
        <div class="skill-item">
            <i class="fab fa-css3-alt"></i>
            <p>CSS3</p>
        </div>
        <div class="skill-item">
            <i class="fab fa-git"></i>
            <p>Git</p>
        </div>
        <div class="skill-item">
            <i class="fab fa-github"></i>
            <p>GitHub</p>
        </div>
        <div class="skill-item">
            <i class="fab fa-postman"></i>
            <p>Postman</p>
        </div>
    </div>

    <hr>

    <h3>📈 GitHub Stats</h3>
    <p align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=Mohamedasddf&show_icons=true&theme=radical" alt="GitHub Stats">
        <br>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mohamedasddf&theme=radical" alt="GitHub Streak">
    </p>

    <hr>

    <h3>✨ My Journey</h3>
    <p align="center">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=16A085&center=true&vCenter=true&width=435&lines=Backend+Developer;Problem+Solver;Restful+API+Specialist;Continuous+Learner" alt="Typing Animation">
    </p>

    <hr>

    <h3>📬 Connect With Me</h3>
    <p align="center">
        <a href="https://www.linkedin.com/in/mohamed-hesham-89800029b/" target="_blank">
            <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
        </a>
        <a href="https://github.com/Mohamedasddf" target="_blank">
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
        </a>
        <a href="mailto:mh1351448@gmail.com" target="_blank">
            <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
        </a>
        <a href="https://mohamedasddf.github.io/portfolio/" target="_blank">
            <img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=web&logoColor=white" alt="Portfolio">
        </a>
    </p>

    <hr>

    <h3>🎓 Education</h3>
    <p>
        **Bachelor of Computer Science** <br>
        EELU University (Expected Graduation: 2026)
    </p>
</body>

</html>
