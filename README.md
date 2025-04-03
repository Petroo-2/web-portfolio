<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Peter Obonyo | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">PeterObonyo</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="burger">
                <i class="fas fa-bars"></i>
            </div>
        </nav>
    </header>

    <main>
        <section id="hero">
            <div class="hero-content">
                <h1>Hi, I'm <span class="highlight">Peter Obonyo</span></h1>
                <p>A passionate developer creating digital solutions</p>
                <a href="#contact" class="btn">Get In Touch</a>
            </div>
            <div class="hero-image">
                <img src="assets/profile.jpg" alt="Peter Obonyo">
            </div>
        </section>

        <section id="about" class="section">
            <h2>About Me</h2>
            <div class="about-content">
                <p>Hi! I'm Peter Obonyo, a passionate web developer with a love for creating functional and beautiful web experiences. I enjoy solving complex problems and turning ideas into reality through code.</p>
                <p>When I'm not coding, you can find me in the research lab or hiking. What drives me is physical health and the intersection of technology with scientific innovation.</p>
            </div>
        </section>

        <section id="skills" class="section">
            <h2>My Skills</h2>
            <div class="skills-container">
                <div class="skill">
                    <i class="fab fa-html5"></i>
                    <h3>HTML5</h3>
                </div>
                <div class="skill">
                    <i class="fab fa-css3-alt"></i>
                    <h3>CSS3</h3>
                </div>
                <div class="skill">
                    <i class="fab fa-js"></i>
                    <h3>JavaScript</h3>
                </div>
                <div class="skill">
                    <i class="fab fa-python"></i>
                    <h3>Python</h3>
                </div>
                <div class="skill">
                    <i class="fas fa-database"></i>
                    <h3>SQL</h3>
                </div>
                <div class="skill">
                    <i class="fab fa-react"></i>
                    <h3>React</h3>
                </div>
            </div>
        </section>

        <section id="education" class="section">
            <h2>Education & Background</h2>
            <div class="education-content">
                <div class="education-item">
                    <h3>Bachelor of Science in Chemistry</h3>
                    <p class="institution">University of Nairobi</p>
                    <p class="duration">2021 - 2025</p>
                    <p>Currently pursuing my degree with a focus on computational chemistry and software development. Achieved Dean's List recognition for academic excellence in 2023-2024. Active member of the University Coding Club where I participate in hackathons and collaborative projects.</p>
                </div>
                <a href="assets/Peter_Obonyo_CV.pdf" class="btn" download>Download My CV</a>
            </div>
        </section>

        <section id="interests" class="section">
            <h2>My Interests</h2>
            <div class="interests-container">
                <div class="interest">
                    <i class="fas fa-code"></i>
                    <h3>Web Development</h3>
                    <p>Exploring modern frameworks and best practices in frontend and backend development.</p>
                </div>
                <div class="interest">
                    <i class="fas fa-robot"></i>
                    <h3>AI in Chemistry</h3>
                    <p>Applying machine learning to solve complex chemical problems and simulations.</p>
                </div>
                <div class="interest">
                    <i class="fas fa-flask"></i>
                    <h3>Computational Chemistry</h3>
                    <p>Using programming to model chemical systems and analyze scientific data.</p>
                </div>
            </div>
        </section>

        <section id="projects" class="section">
            <h2>My Projects</h2>
            <div class="projects-container">
                <div class="project">
                    <img src="assets/recipe-app.jpg" alt="Recipe Finder App">
                    <h3>Recipe Finder App</h3>
                    <p>Created a meal planning app that suggests recipes based on available ingredients. Utilized the Edamam API, React hooks for state management, and Material-UI for consistent styling across components.</p>
                    <a href="https://github.com/yourusername/recipe-finder" class="btn">View Project</a>
                </div>
                <div class="project">
                    <img src="assets/chem-simulator.jpg" alt="Chemical Reaction Simulator">
                    <h3>Chemical Reaction Simulator</h3>
                    <p>Developed a Python application that visualizes chemical reactions using molecular dynamics principles. Implemented with PyGame and RDKit for molecular visualization.</p>
                    <a href="https://github.com/yourusername/chem-simulator" class="btn">View Project</a>
                </div>
                <div class="project">
                    <img src="assets/portfolio-screenshot.jpg" alt="Portfolio Website">
                    <h3>Portfolio Website</h3>
                    <p>Developed this responsive portfolio site from scratch using modern CSS3 techniques including Flexbox and Grid. Implemented smooth scrolling, form validation, and mobile-first design principles.</p>
                    <a href="https://github.com/yourusername/portfolio" class="btn">View Project</a>
                </div>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact Me</h2>
            <div class="contact-container">
                <form class="contact-form">
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
                <div class="contact-info">
                    <h3>Let's Connect!</h3>
                    <p>Feel free to reach out for collaborations or just to say hi!</p>
                    <div class="social-links">
                        <a href="https://github.com/yourusername"><i class="fab fa-github"></i></a>
                        <a href="https://linkedin.com/in/yourprofile"><i class="fab fa-linkedin"></i></a>
                        <a href="https://twitter.com/yourhandle"><i class="fab fa-twitter"></i></a>
                        <a href="mailto:your.email@example.com"><i class="fas fa-envelope"></i></a>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Peter Obonyo. All rights reserved.</p>
        <p>Created for PLP Academy Hackathon Challenge</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
