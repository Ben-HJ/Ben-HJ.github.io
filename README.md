
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Huang Jie, Ben - Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Times New Roman', sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
            padding-top: 60px; /* Offset for fixed nav */
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
            margin: 0 1.5rem;
            font-weight: 500;
        }

        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: linear-gradient(45deg, #6b48ff, #00a8ff);
            color: white;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        .section {
            padding: 6rem 0;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2.5rem;
            margin-top: 2rem;
        }

        .project-card {
            background: #fff;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            border: 1px solid #eee;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2.5rem;
            margin-top: 4rem;
        }

        /* Added styles for PDF section */
        .download-button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #2c3e50;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 1.5rem;
            transition: background-color 0.3s;
        }

        .download-button:hover {
            background-color: #34495e;
        }

        .download-button i {
            margin-right: 8px;
        }

        .competition-background {
            background: #f8f9fa;
            padding: 1.25rem;
            border-left: 4px solid #6b48ff;
            margin: 1.5rem 0;
            border-radius: 4px;
        }

        h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            color: #2c3e50;
        }

        h3 {
            color: #6b48ff;
            margin-bottom: 1rem;
        }

        ul {
            padding-left: 1.5rem;
            margin: 1rem 0;
        }

        li {
            margin-bottom: 0.75rem;
            line-height: 1.8;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Huang Jie, Ben</h1>
            <p>Risk Management Specialist</p>
        </div>
    </section>

    <!-- About Section -->
    <section class="section" id="about">
        <div class="container">
            <h2>Professional Profile</h2>
            <p>I am a dedicated third-year undergraduate student at The Chinese University of Hong Kong (CUHK), pursuing a major in Risk Management Science with a minor in Statistics. My academic journey has equipped me with robust quantitative skills in portfolio evaluation methodologies, derivative pricing models, and statistical analysis, with particular interest in their applications to financial market dynamics.</p>

            <p>Currently serving as a mathematics tutor at SO-IN Yaumatei Education Centre (S.S.) Limited, I have honed my ability to communicate complex analytical concepts to diverse audiences. This experience has strengthened my capacity for technical communication and individualized instruction, while fostering collaborative problem-solving skills.</p>

            <p>My practical experience includes participation in the prestigious Natixis Investment Challenge, where I collaborated with team members to develop and optimize investment portfolios under dynamic market conditions. This hands-on competition enhanced my understanding of risk-return tradeoffs, asset allocation strategies, and performance measurement techniques.</p>

            <h3>Core Competencies</h3>
            <ul>
                <li>Financial risk modeling and quantitative analysis</li>
                <li>Derivative pricing frameworks (Options, Futures, Swaps)</li>
                <li>Portfolio optimization and performance evaluation</li>
                <li>Statistical programming (R, C++, VBA)</li>
                <li>Technical communication and educational mentorship</li>
            </ul>

            <h3>Professional Orientation</h3>
            <p>I am passionate about bridging theoretical risk management concepts with practical financial solutions. My academic pursuits and extracurricular engagements have cultivated a strong foundation in:</p>
            <ul>
                <li>Modern portfolio theory applications</li>
                <li>Financial derivatives market mechanisms</li>
                <li>Data-driven decision making in uncertain environments</li>
            </ul>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section" id="projects">
        <div class="container">
            <h2>Competition Experience</h2>
            
            <div class="projects">
                <div class="project-card">
                    <h3>Natixis Investment Challenge 2023</h3>
                    <p class="competition-background">
                        <strong>Competition Background:</strong> 
                        The Natixis Investment Challenge is an international portfolio management competition 
                        where participants construct and manage virtual investment portfolios under realistic 
                        market constraints. Competitors employ sophisticated financial strategies while 
                        adhering to real-world regulatory frameworks and risk parameters.
                    </p>

                    <h4>Project Overview</h4>
                    <ul>
                        <li>Selected agricultural sector investor profile requiring inflation-hedged growth</li>
                        <li>Designed multi-asset portfolio spanning fixed income (29.45%), equities (36.66%), 
                            and commodities (33.89%)</li>
                        <li>Implemented dynamic allocation strategy with weekly rebalancing</li>
                    </ul>

                    <h4>Key Responsibilities & Strategies</h4>
                    <ul>
                        <li>Led commodities allocation using futures contracts (corn, wheat, soybean)</li>
                        <li>Developed momentum-based entry/exit signals using 50-200 day moving averages</li>
                        <li>Conducted historical backtesting (2015-2022) with Python-based simulation</li>
                        <li>Applied risk parity principles for volatility targeting across asset classes</li>
                        <li>Integrated macroeconomic analysis for sector rotation timing</li>
                    </ul>

                    <h4>Technical Implementation</h4>
                    <ul>
                        <li>Portfolio optimization: Black-Litterman model with views on commodity supercycle</li>
                        <li>Risk management: CVaR constraints at 95% confidence level</li>
                        <li>Performance benchmarking against Bloomberg Agriculture Index</li>
                    </ul>

                    <div class="document-download">
                        <a href="iCloud Drive/Desktop/Natixis.pdf" class="download-button" target="_blank">
                            <i class="fas fa-file-pdf"></i> View Competition Report
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="contact">
        <div class="container">
            <h2>Contact</h2>
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
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Mobile menu toggle
        const nav = document.querySelector('nav');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                nav.style.backgroundColor = 'rgba(51, 51, 51, 0.95)';
            } else {
                nav.style.backgroundColor = '#333';
            }
        });
    </script>
</body>
</html>
