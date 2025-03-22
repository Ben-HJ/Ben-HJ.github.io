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
            <h1>[Your Name]</h1>
            <p>Risk Management Specialist | Quantitative Analyst</p>
            <a href="path/to/your-resume.pdf" class="download-button" download>
                <i class="fas fa-download"></i> Download Resume
            </a>
        </div>
    </section>

    <!-- Rest of your sections here -->
    <!-- About, Skills, Projects, Education, Contact sections remain the same -->

    <footer>
        <p>&copy; 2023 [Your Name]. All rights reserved.</p>
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
