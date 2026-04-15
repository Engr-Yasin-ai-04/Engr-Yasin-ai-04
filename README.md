<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhammad Yasin Khan | AI/ML Engineer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Fira Code', 'Courier New', monospace;
            background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 100%);
            color: #e0e0e0;
            line-height: 1.6;
            padding: 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(10, 10, 10, 0.8);
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 255, 0, 0.1);
            overflow: hidden;
        }

        .header {
            text-align: center;
            padding: 3rem 2rem 2rem;
            background: linear-gradient(135deg, rgba(0, 255, 0, 0.05), rgba(0, 0, 0, 0.5));
        }

        .typing-svg {
            margin-bottom: 1rem;
        }

        h1 {
            font-size: 3rem;
            margin: 1rem 0;
            background: linear-gradient(135deg, #00ff00, #00ff88);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: 700;
        }

        .badges {
            margin: 1.5rem 0;
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .badge {
            transition: transform 0.3s ease;
        }

        .badge:hover {
            transform: translateY(-3px);
        }

        .location {
            color: #888;
            font-size: 1.1rem;
            margin-top: 0.5rem;
        }

        .section {
            padding: 2rem;
            border-bottom: 1px solid rgba(0, 255, 0, 0.1);
        }

        .section:last-child {
            border-bottom: none;
        }

        .section-title {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            color: #00ff00;
            border-left: 4px solid #00ff00;
            padding-left: 1rem;
        }

        .experience-table {
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            overflow: hidden;
        }

        th, td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid rgba(0, 255, 0, 0.1);
        }

        th {
            background: rgba(0, 255, 0, 0.1);
            color: #00ff00;
            font-weight: 600;
        }

        tr:hover {
            background: rgba(0, 255, 0, 0.05);
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 0.8rem;
        }

        .skill-tag {
            background: rgba(0, 255, 0, 0.1);
            border: 1px solid rgba(0, 255, 0, 0.3);
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            transition: all 0.3s ease;
        }

        .skill-tag:hover {
            background: rgba(0, 255, 0, 0.2);
            transform: translateY(-2px);
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        .project-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 1rem;
            border-radius: 10px;
            border: 1px solid rgba(0, 255, 0, 0.2);
            transition: all 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            border-color: #00ff00;
            box-shadow: 0 5px 20px rgba(0, 255, 0, 0.1);
        }

        .project-card h3 {
            color: #00ff00;
            margin-bottom: 0.5rem;
        }

        .github-stats {
            text-align: center;
        }

        .github-stats img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .contact {
            text-align: center;
            font-size: 1.2rem;
        }

        .contact a {
            color: #00ff00;
            text-decoration: none;
            border-bottom: 1px solid #00ff00;
        }

        .contact a:hover {
            color: #00ff88;
        }

        .footer {
            text-align: center;
            padding: 2rem;
            background: linear-gradient(135deg, rgba(0, 255, 0, 0.05), rgba(0, 0, 0, 0.5));
            font-size: 1.2rem;
            color: #00ff00;
        }

        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .section {
                padding: 1.5rem;
            }
            
            th, td {
                padding: 0.75rem;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <div class="typing-svg">
                <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=3000&pause=500&color=00FF00&center=true&vCenter=true&width=500&lines=Muhammad+Yasin+Khan;AI%2FML+Engineer;4+Internships;Open+To+Work" alt="Typing SVG" />
            </div>
            
            <h1>Muhammad Yasin Khan</h1>
            
            <div class="badges">
                <a href="https://www.linkedin.com/in/engr-m-yasin-khan" class="badge" target="_blank">
                    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
                </a>
                <a href="mailto:engr.yasin.ai@gmail.com" class="badge">
                    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
                </a>
            </div>
            
            <div class="location">
                📍 Swat, Pakistan
            </div>
        </div>

        <!-- Experience Section -->
        <div class="section">
            <h2 class="section-title">💼 Experience</h2>
            <div class="experience-table">
                <table>
                    <thead>
                        <tr>
                            <th>Position</th>
                            <th>Company</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>ML Intern</td><td>Internee.pk</td></tr>
                        <tr><td>AI/ML Intern</td><td>DevelopersHub</td></tr>
                        <tr><td>Data Science Intern</td><td>Arch Technologies</td></tr>
                        <tr><td>AI Intern</td><td>NCAI Pakistan</td></tr>
                        <tr><td>AI Engineer</td><td>UEAS Swat</td></tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- Skills Section -->
        <div class="section">
            <h2 class="section-title">🛠️ Skills</h2>
            <div class="skills">
                <span class="skill-tag">Python</span>
                <span class="skill-tag">TensorFlow</span>
                <span class="skill-tag">PyTorch</span>
                <span class="skill-tag">OpenCV</span>
                <span class="skill-tag">YOLOv8</span>
                <span class="skill-tag">Django</span>
            </div>
        </div>

        <!-- Projects Section -->
        <div class="section">
            <h2 class="section-title">🚀 Projects</h2>
            <div class="projects">
                <div class="project-card">
                    <h3>Pneumonia Detection</h3>
                    <p>AI-powered medical diagnosis system</p>
                </div>
                <div class="project-card">
                    <h3>Face Detection</h3>
                    <p>Real-time face detection using YOLOv8</p>
                </div>
                <div class="project-card">
                    <h3>ML Projects</h3>
                    <p>Various machine learning implementations</p>
                </div>
            </div>
        </div>

        <!-- Education Section -->
        <div class="section">
            <h2 class="section-title">🎓 Education</h2>
            <div class="project-card" style="max-width: 400px;">
                <h3>BS Artificial Intelligence</h3>
                <p>UEAS Swat</p>
            </div>
        </div>

        <!-- GitHub Stats Section -->
        <div class="section">
            <h2 class="section-title">📊 GitHub Stats</h2>
            <div class="github-stats">
                <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical" alt="GitHub Stats" width="45%" />
            </div>
        </div>

        <!-- Contact Section -->
        <div class="section">
            <h2 class="section-title">📧 Contact</h2>
            <div class="contact">
                <a href="mailto:engr.yasin.ai@gmail.com">engr.yasin.ai@gmail.com</a>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            ⭐ Open for Work ⭐
        </div>
    </div>
</body>
</html>
