
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
            padding-top: 60px; /* Added padding to prevent content from being hidden behind fixed nav */
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
            font-size: 0.9rem;
        }

        nav a:hover {
            color: #6b48ff;
        }

        .hero {
            height: 70vh; /* Reduced height */
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: #f8f9fa;
            color: #333;
            padding: 0 2rem;
        }

        .hero-content h1 {
            font-size: 2.5rem; /* Reduced size */
            margin-bottom: 1rem;
            line-height: 1.2;
        }

        .hero-content p {
            font-size: 1.1rem;
            color: #666;
            margin-bottom: 1.5rem;
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

        /* Media Queries for Mobile */
        @media (max-width: 768px) {
            .hero {
                height: 60vh;
                padding: 0 1rem;
            }

            .hero-content h1 {
                font-size: 2rem;
            }

            .hero-content p {
                font-size: 1rem;
            }

            nav a {
                margin: 0 0.5rem;
                font-size: 0.8rem;
            }

            .container {
                padding: 2rem 1rem;
            }

            .section {
                padding: 2rem 0;
            }
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
            <h1>Huang Jie, Ben</h1>
            <p>Risk Management Specialist</p>
            <a href="HuangJie_CV.pdf" class="download-button" target="_blank">
                <i class="fas fa-file-pdf"></i> View Resume
            </a>
        </div>
    </section>

    <section class="section" id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>I am a dedicated third-year undergraduate student at The Chinese University of Hong Kong (CUHK), pursuing a major in Risk Management Science with a minor in Statistics. My academic journey has equipped me with robust quantitative skills in portfolio evaluation methodologies, derivative pricing models, and statistical analysis, with particular interest in their applications to financial market dynamics.</p>
            <p>Currently serving as a mathematics tutor at SO-IN Yaumatei Education Centre (S.S.) Limited, I have honed my ability to communicate complex analytical concepts to diverse audiences. This experience has strengthened my capacity for technical communication and individualized instruction, while fostering collaborative problem-solving skills.</p>
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
                    <h3>Programming Languages</h3>
                    <p>R, C++</p>
                </div>
                <div class="skill-card">
                    <h3>Financial Tools</h3>
                    <p>Excel VBA</p>
                </div>
                <div class="skill-card">
                    <h3>Risk Management</h3>
                    <p>VaR, Stochastic Calculus</p>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="projects">
        <div class="container">
            <h2>Projects & Competitions</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Investment Strategy Challenge 2024</h3>
                    <p>Developed multi-asset portfolio for agricultural sector investor, implementing momentum strategies and risk parity principles.</p>
                    <a href="Natixis.pdf" class="download-button" target="_blank">
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
                    <p>2022 - Present</p>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>
                <a href="mailto:benhj0909@gmail.com" class="social-link">
                    <i class="fas fa-envelope"></i> Email
                </a><br>
                <a href="https://linkedin.com/in/jie-huang20040909" target="_blank" class="social-link">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
            </p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Huang Jie. All rights reserved.</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth',
                    block: 'start'
                });
            });
        });
    </script>
</body>
</html>
