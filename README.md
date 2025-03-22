<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            line-height: 1.4;
            color: #333;
        }

        nav {
            background: #333;
            padding: 1rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #6b48ff;
        }

        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: #f8f9fa;
            color: #333;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
        }

        .hero-content p {
            font-size: 1.25rem;
            color: #666;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        .section {
            padding: 4rem 0;
        }

        .section h2 {
            font-size: 2rem;
            margin-bottom: 2rem;
            color: #2c3e50;
        }

        .section p {
            margin-bottom: 1rem;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .skill-card {
            background: #f5f5f5;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .project-card {
            background: #f5f5f5;
            padding: 1.5rem;
            border-radius: 8px;
        }

        .education-timeline {
            margin-top: 2rem;
        }

        .timeline-item {
            padding: 1.5rem;
            border-left: 3px solid #6b48ff;
            margin-bottom: 1.5rem;
        }

        .download-button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #2c3e50;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 1rem;
            transition: background-color 0.3s;
        }

        .download-button:hover {
            background-color: #34495e;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#education">Education</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <div class="hero-content">
            <h1>[Your Name]</h1>
            <p>Risk Management Specialist | Quantitative Analyst</p>
            <a href="path/to/your-resume.pdf" class="download-button" download>
                <i class="fas fa-download"></i> Download Resume
            </a>
        </div>
    </section>

    <section class="section" id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>I am a dedicated third-year undergraduate student at The Chinese University of Hong Kong (CUHK), pursuing a major in Risk Management Science with a minor in Statistics. My academic journey has equipped me with robust quantitative skills in portfolio evaluation methodologies, derivative pricing models, and statistical analysis, with particular interest in their applications to financial market dynamics.</p>
            <p>Currently serving as a mathematics and statistics tutor at SOIN Limited, I have honed my ability to communicate complex analytical concepts to diverse audiences. This experience has strengthened my capacity for technical communication and individualized instruction, while fostering collaborative problem-solving skills.</p>
            <p>My practical experience includes participation in the prestigious Natixis Investment Challenge, where I collaborated with team members to develop and optimize investment portfolios under dynamic market conditions. This hands-on competition enhanced my understanding of risk-return tradeoffs, asset allocation strategies, and performance measurement techniques.</p>
        </div>
    </section>

    <section class="section" id="skills">
        <div class="container">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>Quantitative Analysis</h3>
                    <p>Portfolio optimization, Risk modeling, Derivative pricing</p>
                </div>
                <div class="skill-card">
                    <h3>Programming</h3>
                    <p>Python, R, MATLAB, SQL</p>
                </div>
                <div class="skill-card">
                    <h3>Financial Tools</h3>
                    <p>Bloomberg Terminal, Excel VBA, Tableau</p>
                </div>
                <div class="skill-card">
                    <h3>Risk Management</h3>
                    <p>VaR, CVaR, Stress testing, Scenario analysis</p>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="projects">
        <div class="container">
            <h2>Projects & Competitions</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Natixis Investment Challenge 2023</h3>
                    <p>Developed multi-asset portfolio for agricultural sector investor, implementing momentum strategies and risk parity principles.</p>
                    <a href="path/to/your-file.pdf" class="download-button" target="_blank">
                        <i class="fas fa-file-pdf"></i> View Report
                    </a>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="education">
        <div class="container">
            <h2>Education</h2>
            <div class="education-timeline">
                <div class="timeline-item">
                    <h3>The Chinese University of Hong Kong</h3>
                    <p>BSc in Risk Management Science, Minor in Statistics</p>
                    <p>2021 - Present</p>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>
                <a href="mailto:your@email.com" class="social-link">
                    <i class="fas fa-envelope"></i> Email
                </a><br>
                <a href="https://github.com/yourusername" target="_blank" class="social-link">
                    <i class="fab fa-github"></i> GitHub
                </a><br>
                <a href="https://linkedin.com/in/yourprofile" target="_blank" class="social-link">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
            </p>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 [Your Name]. All rights reserved.</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
