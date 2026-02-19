<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kaustab Das - Data Analyst & ML Enthusiast</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0F2027 0%, #203A43 50%, #2C5364 100%);
            min-height: 100vh;
            padding: 20px;
            color: #fff;
            position: relative;
            overflow-x: hidden;
        }body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 20% 50%, rgba(0, 255, 179, 0.05) 0%, transparent 50%),
                        radial-gradient(circle at 80% 80%, rgba(0, 212, 255, 0.05) 0%, transparent 50%);
            pointer-events: none;
            animation: backgroundPulse 10s ease-in-out infinite;
            z-index: 0;
        }
 @keyframes backgroundPulse {
            0%, 100% { opacity: 0.5; }
            50% { opacity: 1; }
        }

.container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5), 0 0 100px rgba(0, 255, 179, 0.1);
            animation: fadeIn 1s ease-in, containerGlow 4s ease-in-out infinite;
            position: relative;
            z-index: 1;
        }

@keyframes containerGlow {
            0%, 100% { box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5), 0 0 100px rgba(0, 255, 179, 0.1); }
            50% { box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5), 0 0 150px rgba(0, 212, 255, 0.2); }
        }

@keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

@keyframes slideIn {
            from { opacity: 0; transform: translateX(-30px); }
            to { opacity: 1; transform: translateX(0); }
        }

 @keyframes slideInRight {
            from { opacity: 0; transform: translateX(30px); }
            to { opacity: 1; transform: translateX(0); }
        }

@keyframes bounceIn {
            0% { opacity: 0; transform: scale(0.3); }
            50% { opacity: 1; transform: scale(1.05); }
            70% { transform: scale(0.9); }
            100% { transform: scale(1); }
        }

 @keyframes glow {
            0%, 100% { box-shadow: 0 0 20px rgba(0, 255, 179, 0.5); }
            50% { box-shadow: 0 0 30px rgba(0, 255, 179, 0.8); }
        }

@keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.05); opacity: 0.9; }
        }

 @keyframes colorShift {
            0%, 100% { border-color: rgba(0, 255, 179, 0.5); }
            25% { border-color: rgba(0, 212, 255, 0.5); }
            50% { border-color: rgba(0, 153, 255, 0.5); }
            75% { border-color: rgba(0, 212, 255, 0.5); }
        }

@keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

 header {
            background: linear-gradient(135deg, #00ffb3 0%, #00d4ff 50%, #0099ff 100%);
            padding: 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            animation: shine 3s infinite;
        }

@keyframes shine {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

  h1 {
            font-size: 3em;
            color: #0F2027;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
            position: relative;
            z-index: 1;
            animation: float 3s ease-in-out infinite;
        }

.tagline {
            font-size: 1.2em;
            color: #0F2027;
            font-weight: 500;
            position: relative;
            z-index: 1;
            animation: fadeIn 1.5s ease-in;
        }

 .contact-info {
            margin-top: 20px;
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            position: relative;
            z-index: 1;
        }

 .contact-info a {
            color: #0F2027;
            text-decoration: none;
            padding: 8px 15px;
            background: rgba(255,255,255,0.9);
            border-radius: 20px;
            transition: all 0.3s ease;
            font-weight: 500;
            animation: bounceIn 0.6s ease-out;
            animation-fill-mode: both;
        }

  .contact-info a:nth-child(1) { animation-delay: 0.1s; }
        .contact-info a:nth-child(2) { animation-delay: 0.2s; }
        .contact-info a:nth-child(3) { animation-delay: 0.3s; }
        .contact-info a:nth-child(4) { animation-delay: 0.4s; }

 .contact-info a:hover {
            background: #fff;
            transform: translateY(-5px) scale(1.1);
            box-shadow: 0 8px 20px rgba(0,0,0,0.4);
            animation: pulse 0.5s ease-in-out;
        }

 .content {
            padding: 40px;
        }

  .section {
            margin-bottom: 40px;
            animation: slideIn 0.8s ease-out;
            background: linear-gradient(135deg, rgba(0, 255, 179, 0.03), rgba(0, 212, 255, 0.02));
            padding: 25px;
            border-radius: 15px;
            border-left: 4px solid #00ffb3;
            border: 1px solid rgba(0, 255, 179, 0.1);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

.section::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(0, 255, 179, 0.05) 0%, transparent 70%);
            opacity: 0;
            transition: opacity 0.4s ease;
        }
 .section:hover::before {
            opacity: 1;
            animation: shine 3s linear infinite;
        }

   .section:hover {
       background: linear-gradient(135deg, rgba(0, 255, 179, 0.08), rgba(0, 212, 255, 0.05));
            transform: translateX(5px);
            border-left: 4px solid #00d4ff;
            box-shadow: 0 10px 30px rgba(0, 255, 179, 0.2), inset 0 0 20px rgba(0, 255, 179, 0.05);
        }

.section:nth-child(odd) {
            animation: slideIn 0.8s ease-out;
        }

 .section:nth-child(even) {
            animation: slideInRight 0.8s ease-out;
        }

 h2 {
            color: #00ffb3;
            font-size: 2em;
            margin-bottom: 20px;
            border-bottom: 2px solid #00ffb3;
            padding-bottom: 10px;
            display: inline-block;
            position: relative;
            animation: glow 3s ease-in-out infinite;
        }

 h2::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background: linear-gradient(90deg, #00ffb3, #00d4ff, #0099ff);
            animation: borderExpand 2s ease-in-out infinite;
        }

 @keyframes borderExpand {
            0%, 100% { width: 0%; }
            50% { width: 100%; }
        }

h3 {
            color: #00d4ff;
            font-size: 1.3em;
            margin: 15px 0 10px 0;
            animation: fadeIn 1s ease-in;
            text-shadow: 0 0 10px rgba(0, 212, 255, 0.3);
        }
    .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

 .skill-category {
            background: linear-gradient(135deg, rgba(0, 255, 179, 0.1), rgba(0, 212, 255, 0.1));
            padding: 20px;
            border-radius: 10px;
            border: 1px solid rgba(0, 255, 179, 0.3);
            transition: all 0.4s ease;
            animation: fadeIn 0.8s ease-in;
            position: relative;
            overflow: hidden;
        }

  .skill-category::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 255, 179, 0.2), transparent);
            transition: left 0.5s ease;
        }

  .skill-category:hover::before {
            left: 100%;
        }

 .skill-category:hover {
            transform: translateY(-8px) scale(1.02);
            border-color: #00ffb3;
            box-shadow: 0 15px 40px rgba(0, 255, 179, 0.3), 0 0 30px rgba(0, 255, 179, 0.2);
            background: linear-gradient(135deg, rgba(0, 255, 179, 0.15), rgba(0, 212, 255, 0.15));
        }

 .skill-category h4 {
            color: #00ffb3;
            margin-bottom: 10px;
            font-size: 1.1em;
            position: relative;
            z-index: 1;
            animation: fadeIn 1s ease-in;
            text-shadow: 0 0 10px rgba(0, 255, 179, 0.4);
            transition: all 0.3s ease;
        }
  .skill-category:hover h4 {
            transform: scale(1.1);
            text-shadow: 0 0 20px rgba(0, 255, 179, 0.8);
        }

 .skill-category p {
            color: #ddd;
            line-height: 1.6;
            position: relative;
            z-index: 1;
            transition: all 0.3s ease;
        }
    .skill-category:hover p {
            color: #fff;
        }

 .education-item, .experience-item, .project-item {
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.05), rgba(0, 153, 255, 0.03));
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            border-left: 3px solid #00d4ff;
            border: 1px solid rgba(0, 212, 255, 0.2);
            transition: all 0.4s ease;
            animation: slideIn 0.6s ease-out;
            position: relative;
            overflow: hidden;
        }

 .education-item::before, .experience-item::before, .project-item::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 3px;
            height: 0;
            background: linear-gradient(180deg, #00ffb3, #00d4ff, #0099ff);
            transition: height 0.4s ease;
        }

.education-item:hover::before, .experience-item:hover::before, .project-item:hover::before {
            height: 100%;
        }

 .education-item:hover, .experience-item:hover, .project-item:hover {
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.12), rgba(0, 153, 255, 0.08));
            transform: translateX(15px) scale(1.02);
            border-left: 3px solid #00ffb3;
            box-shadow: 0 10px 30px rgba(0, 212, 255, 0.3), inset 0 0 30px rgba(0, 212, 255, 0.05);
        }

 .date {
            color: #00ffb3;
            font-weight: 600;
            font-size: 0.9em;
            display: inline-block;
            animation: fadeIn 1s ease-in;
            text-shadow: 0 0 10px rgba(0, 255, 179, 0.3);
            transition: all 0.3s ease;
        }

.date:hover {
            transform: scale(1.1);
            text-shadow: 0 0 15px rgba(0, 255, 179, 0.6);
        }

 .percentage {
            color: #00d4ff;
            font-weight: 600;
            animation: fadeIn 1.2s ease-in;
            text-shadow: 0 0 10px rgba(0, 212, 255, 0.3);
            transition: all 0.3s ease;
        }

.percentage:hover {
            transform: scale(1.1);
            text-shadow: 0 0 15px rgba(0, 212, 255, 0.6);
        }

 ul {
            list-style: none;
            padding-left: 0;
        }

ul li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
            color: #ddd;
            line-height: 1.6;
            animation: slideIn 0.6s ease-out;
            transition: all 0.3s ease;
        }

 ul li:hover {
            padding-left: 30px;
            color: #fff;
        }

 ul li::before {
            content: '▹';
            position: absolute;
            left: 0;
            color: #00ffb3;
            font-size: 1.2em;
            animation: pulse 2s ease-in-out infinite;
            text-shadow: 0 0 10px rgba(0, 255, 179, 0.5);
        }

ul li:hover::before {
            animation: float 1s ease-in-out infinite;
            text-shadow: 0 0 20px rgba(0, 255, 179, 0.8);
        }

 .badge {
            display: inline-block;
            background: linear-gradient(135deg, #00ffb3, #00d4ff);
            color: #0F2027;
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.85em;
            font-weight: 600;
            margin-right: 8px;
            margin-bottom: 8px;
            transition: all 0.3s ease;
            animation: bounceIn 0.5s ease-out;
            cursor: default;
        }

 .badge:hover {
            transform: scale(1.15) rotate(5deg);
            box-shadow: 0 5px 15px rgba(0, 255, 179, 0.5);
            background: linear-gradient(135deg, #00d4ff, #00ffb3);
        }

 .project-links {
            margin-top: 10px;
        }

 .project-links a {
            color: #00ffb3;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            display: inline-block;
            padding: 5px 10px;
            border: 1px solid rgba(0, 255, 179, 0.3);
            border-radius: 5px;
            animation: fadeIn 1s ease-in;
        }

 .project-links a:hover {
            color: #fff;
            background: linear-gradient(135deg, #00ffb3, #00d4ff);
            transform: translateY(-3px) scale(1.05);
            box-shadow: 0 5px 20px rgba(0, 255, 179, 0.5);
            border-color: #00ffb3;
            animation: pulse 0.5s ease-in-out;
        }

 .achievements-list {
            background: linear-gradient(135deg, rgba(0, 255, 179, 0.05), rgba(0, 212, 255, 0.03));
            padding: 20px;
            border-radius: 10px;
            margin-top: 15px;
            border: 1px solid rgba(0, 255, 179, 0.2);
            animation: fadeIn 1s ease-in;
            transition: all 0.4s ease;
        }

.achievements-list:hover {
            background: linear-gradient(135deg, rgba(0, 255, 179, 0.1), rgba(0, 212, 255, 0.08));
            box-shadow: 0 10px 30px rgba(0, 255, 179, 0.2), inset 0 0 20px rgba(0, 255, 179, 0.05);
            transform: scale(1.02);
        }

 @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
 .content {
                padding: 20px;
            }
            
 .skills-grid {
                grid-template-columns: 1fr;
            }

 .contact-info {
                flex-direction: column;
                align-items: center;
            }
        }

.certifications-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

.cert-card {
            background: linear-gradient(135deg, rgba(0, 153, 255, 0.1), rgba(0, 255, 179, 0.1));
            padding: 15px;
            border-radius: 10px;
            border: 1px solid rgba(0, 212, 255, 0.3);
            transition: all 0.4s ease;
            animation: fadeIn 0.6s ease-in;
            position: relative;
            overflow: hidden;
        }

.cert-card::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            border-radius: 50%;
            background: rgba(0, 255, 179, 0.1);
            transform: translate(-50%, -50%);
            transition: width 0.4s ease, height 0.4s ease;
        }

 .cert-card:hover::after {
            width: 300px;
            height: 300px;
        }

 .cert-card:hover {
            transform: translateY(-5px) scale(1.03);
            box-shadow: 0 10px 30px rgba(0, 212, 255, 0.4), 0 0 20px rgba(0, 255, 179, 0.3);
            border-color: #00ffb3;
        }

 .cert-card h4 {
            position: relative;
            z-index: 1;
        }

 .cert-card p {
            position: relative;
            z-index: 1;
        }

 .github-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

   .github-stats img {
            width: 100%;
            border-radius: 10px;
            transition: all 0.4s ease;
            animation: fadeIn 1s ease-in;
            border: 2px solid rgba(0, 255, 179, 0.2);
        }

 .github-stats img:hover {
            transform: scale(1.08) rotate(1deg);
            box-shadow: 0 15px 40px rgba(0, 255, 179, 0.4), 0 0 30px rgba(0, 212, 255, 0.3);
            border-color: #00ffb3;
            animation: pulse 1s ease-in-out infinite;
        }

 .skill-icons {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
            justify-content: center;
        }

 .skill-icons img {
            transition: all 0.3s ease;
            animation: bounceIn 0.8s ease-out;
            filter: drop-shadow(0 0 5px rgba(0, 255, 179, 0.3));
        }

 .skill-icons img:hover {
            transform: scale(1.2) translateY(-5px);
            filter: drop-shadow(0 5px 15px rgba(0, 255, 179, 0.6));
            animation: float 1s ease-in-out infinite;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>KAUSTAB DAS</h1>
            <p class="tagline">Data Analyst & Machine Learning Enthusiast</p>
            <div class="contact-info">
                <a href="mailto:kaustabdas2003@gmail.com">📧 kaustabdas2003@gmail.com</a>
                <a href="https://www.linkedin.com/in/kaustab-das-35ab03294/" target="_blank">💼 LinkedIn</a>
                <a href="https://github.com/Kaustab2003" target="_blank">💻 GitHub</a>
                <a href="tel:9051840120">📱 9051840120</a>
            </div>
        </header>

 <div class="content">
            <!-- Objective Section -->
            <div class="section">
                <h2>💡 Objective</h2>
                <p style="color: #ddd; line-height: 1.8; font-size: 1.05em;">
                    Data Analyst & Machine Learning Enthusiast skilled in Python, SQL, Tableau, and predictive modeling, 
                    experienced in building scalable data pipelines, analytical dashboards, and ML models for business decision-making.
                </p>
            </div>
 <!-- GitHub Stats Section -->
            <div class="section">
                <h2>📊 GitHub Stats & Activity</h2>
                <div class="github-stats">
                    <img src="https://github-readme-stats.vercel.app/api?username=Kaustab2003&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=percentile&title_color=00ffb3&icon_color=00d4ff&text_color=fff&bg_color=0F2027" alt="GitHub Stats" />
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Kaustab2003&theme=tokyonight&hide_border=true&background=0F2027&stroke=00ffb3&ring=00d4ff&fire=00ffb3&currStreakLabel=00d4ff" alt="GitHub Streak" />
                </div>
                <div style="margin-top: 20px; text-align: center;">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kaustab2003&layout=compact&theme=tokyonight&hide_border=true&title_color=00ffb3&text_color=fff&bg_color=0F2027" alt="Top Languages" style="border-radius: 10px;" />
                </div>
            </div>

            <!-- Skills Section -->
 <div class="section">
                <h2>🛠️ Skills Summary</h2>
                
                <!-- Skill Icons -->
 <div class="skill-icons">
                    <img src="https://skillicons.dev/icons?i=python,java,pytorch,tensorflow,sklearn" alt="Programming Languages" />
                    <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,sqlite" alt="Databases" />
                    <img src="https://skillicons.dev/icons?i=git,github,vscode,docker,linux" alt="Tools" />
                </div>
                
 <div class="skills-grid">
                    <div class="skill-category">
                        <h4>Programming</h4>
                        <p>Python, SQL, Java</p>
                    </div>
                    <div class="skill-category">
                        <h4>Libraries</h4>
                        <p>Pandas, NumPy, Matplotlib, Plotly, Seaborn, PyTorch</p>
                    </div>
                    <div class="skill-category">
                        <h4>Data Tools</h4>
                        <p>Tableau, Advanced Excel</p>
                    </div>
                    <div class="skill-category">
                        <h4>Concepts</h4>
                        <p>EDA, Feature Engineering, Machine Learning, Deep Learning</p>
                    </div>
                    <div class="skill-category">
                        <h4>Version Control</h4>
                        <p>Git, GitHub</p>
                    </div>
                </div>
            </div>

            <!-- Education Section -->
 <div class="section">
                <h2>🎓 Education</h2>
                <div class="education-item">
                    <h3>BTech in Computer Science & Engineering</h3>
                    <p><strong>University of Engineering and Management, Kolkata</strong></p>
                    <p class="date">2022 - 2026</p>
                    <p class="percentage">CGPA: 77.9%</p>
                </div>
                <div class="education-item">
                    <h3>Higher Secondary Education</h3>
                    <p><strong>Ramakrishna Mission Ashram Baranagar</strong></p>
                    <p class="date">2021 - 2022</p>
                    <p class="percentage">Percentage: 74.8%</p>
                </div>
                <div class="education-item">
                    <h3>Secondary Education</h3>
                    <p><strong>Patha Bhavan Dankuni</strong></p>
                    <p class="date">2020</p>
                    <p class="percentage">Percentage: 85.7%</p>
                </div>
            </div>

            <!-- Certifications Section -->
 <div class="section">
                <h2>📜 Training & Certifications</h2>
                <div class="certifications-grid">
                    <div class="cert-card">
                        <h4 style="color: #00ffb3; margin-bottom: 5px;">Data Analytics & Visualization</h4>
                        <p style="color: #ddd;">Accenture</p>
                    </div>
                    <div class="cert-card">
                        <h4 style="color: #00ffb3; margin-bottom: 5px;">Data Analytics Job Simulation</h4>
                        <p style="color: #ddd;">Deloitte</p>
                    </div>
                    <div class="cert-card">
                        <h4 style="color: #00ffb3; margin-bottom: 5px;">GenAI Powered Data Analytics</h4>
                        <p style="color: #ddd;">Tata</p>
                    </div>
                    <div class="cert-card">
                        <h4 style="color: #00ffb3; margin-bottom: 5px;">Data Science</h4>
                        <p style="color: #ddd;">Infosys</p>
                    </div>
                </div>
            </div>

            <!-- Experience Section -->
 <div class="section">
                <h2>💼 Experience</h2>
                
 <div class="experience-item">
                    <h3>AI & Machine Learning Intern</h3>
                    <p><strong>Edunet Foundation | SkillsBuild Program (by IBM)</strong></p>
                    <p class="date">June 2025 - July 2025</p>
                    <ul>
                        <li>Selected for a competitive 6-week AI/ML internship under the IBM SkillsBuild program</li>
                        <li>Gained hands-on experience with AI, ML, and Azure, utilizing Generative AI and Copilot to build projects</li>
                        <li>Built projects that automate tasks and solve real-world challenges</li>
                    </ul>
                </div>

  <div class="experience-item">
                    <h3>Data Analytics Intern</h3>
                    <p><strong>Infosys Springboard</strong></p>
                    <p class="date">October 2025 - December 2025</p>
                    <ul>
                        <li><strong>Data Analysis & Visualization:</strong> Used Python (Pandas, NumPy, Matplotlib, Plotly) to process flight data and created clear visual maps and charts to track delays and route patterns</li>
                        <li><strong>Operational Insights:</strong> Analysed the main causes of flight cancellations and delays, summarizing key findings in a final report and GitHub repository</li>
                    </ul>
                </div>
            </div>

            <!-- Projects Section -->
<div class="section">
                <h2>🚀 Projects</h2>
                
  <div class="project-item">
                    <h3>AirFly Insights – U.S. Aviation Performance Dashboard</h3>
                    <div style="margin-bottom: 10px;">
                        <span class="badge">Python</span>
                        <span class="badge">Streamlit</span>
                        <span class="badge">Plotly</span>
                        <span class="badge">Pandas</span>
                        <span class="badge">Data Visualization</span>
                    </div>
                    <ul>
                        <li><strong>Overview:</strong> Developed a Streamlit application to analyse 5.8M flight records, featuring 50+ interactive visualizations (Plotly, Folium) for route and delay analysis</li>
                        <li><strong>Data Engineering:</strong> Built a Python pipeline to clean data and engineer 40+ custom features, including delay categories and seasonal metrics</li>
                        <li><strong>Insights:</strong> Uncovered critical operational trends, identifying carrier efficiency gaps and correlations between evening departures and delay severity</li>
                    </ul>
                    <div class="project-links">
                        <a href="https://github.com/Kaustab2003/airfly" target="_blank">🔗 View on GitHub</a>
                    </div>
                </div>

 <div class="project-item">
                    <h3>E-Commerce Product Price Prediction</h3>
                    <div style="margin-bottom: 10px;">
                        <span class="badge">PyTorch</span>
                        <span class="badge">Deep Learning</span>
                        <span class="badge">Neural Networks</span>
                        <span class="badge">ML</span>
                        <span class="badge">Computer Vision</span>
                    </div>
                    <ul>
                        <li><strong>Architecture:</strong> Designed a custom Multimodal Neural Network in PyTorch that fuses text and image data to predict product prices. Integrated MPNet (768-dim) for semantic text embeddings and EfficientNet-B0 (1280-dim) for image feature extraction</li>
                        <li><strong>Advanced Fusion:</strong> Implemented Attention Mechanisms and Residual Blocks to dynamically weight text vs. visual features, significantly improving information flow and model stability</li>
                        <li><strong>Feature Engineering:</strong> Developed a pipeline to extract Item Pack Quantity (IPQ) from unstructured text and engineered non-linear features (log, sqrt) to capture pricing trends</li>
                        <li><strong>Optimization:</strong> Utilized Huber Loss to handle price outliers, OneCycleLR for efficient convergence, and AdamW optimization</li>
                        <li><strong>Impact:</strong> Achieved an R² Score of 0.27 and MAE of $11.69, outperforming text-only baselines by 105.7% and reducing error by 8.3%</li>
                    </ul>
                    <div class="project-links">
                        <a href="https://github.com/Kaustab2003/Smart-Product-Pricing-Amazon" target="_blank">🔗 View on GitHub</a>
                    </div>
                </div>
            </div>

            <!-- Achievements Section -->
<div class="section">
                <h2>🏆 Achievements & Participation</h2>
                <div class="achievements-list">
                    <ul>
                        <li>Completed the <strong>JUSPAY Hiring Challenge 2025</strong>, demonstrating strong problem-solving skills and technical expertise in a competitive coding environment</li>
                        <li>Participated in <strong>Adobe India Hackathon</strong>, solving real-world challenges in a competitive tech environment</li>
                        <li>Participant, <strong>EY Hackathon 6</strong>, Advanced past the preliminary round (Round 1) by solving technical challenges</li>
                    </ul>
                </div>
            </div>

            <!-- Languages & Interests Section -->
  <div class="section">
                <h2>🌐 Languages & Interests</h2>
                <div class="skills-grid">
                    <div class="skill-category">
                        <h4>Languages</h4>
                        <p>English, Bengali, Hindi</p>
                    </div>
                    <div class="skill-category">
                        <h4>Interests</h4>
                        <p>Participating in online Hackathons, Playing Football</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
