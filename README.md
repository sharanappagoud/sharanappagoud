<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sharan Appagoud - GitHub Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <header class="profile-header">
            <div class="profile-image">
                <img src="https://github.com/sharanappagoud.png" alt="Profile Picture" id="profileImg">
            </div>
            <h1 class="name">Sharan Appagoud</h1>
            <p class="tagline">Full Stack Developer | Open Source Enthusiast</p>
            <div class="social-links">
                <a href="https://github.com/sharanappagoud" target="_blank" class="social-btn">
                    <span>GitHub</span>
                </a>
                <a href="https://linkedin.com/in/sharanappagoud" target="_blank" class="social-btn">
                    <span>LinkedIn</span>
                </a>
                <a href="mailto:your.email@example.com" class="social-btn">
                    <span>Email</span>
                </a>
            </div>
        </header>

        <!-- About Section -->
        <section class="about-section">
            <h2>About Me</h2>
            <p>
                👋 Hi there! I'm a passionate developer who loves building amazing web applications.
                I enjoy learning new technologies and contributing to open source projects.
            </p>
        </section>

        <!-- Skills Section -->
        <section class="skills-section">
            <h2>Tech Stack</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <span class="skill-icon">🌐</span>
                    <h3>Frontend</h3>
                    <p>HTML, CSS, JavaScript, React</p>
                </div>
                <div class="skill-card">
                    <span class="skill-icon">⚙️</span>
                    <h3>Backend</h3>
                    <p>Node.js, Express, Python</p>
                </div>
                <div class="skill-card">
                    <span class="skill-icon">💾</span>
                    <h3>Database</h3>
                    <p>MongoDB, MySQL, PostgreSQL</p>
                </div>
                <div class="skill-card">
                    <span class="skill-icon">🛠️</span>
                    <h3>Tools</h3>
                    <p>Git, Docker, VS Code</p>
                </div>
            </div>
        </section>

        <!-- GitHub Stats Section -->
        <section class="stats-section">
            <h2>GitHub Stats</h2>
            <div class="stats-grid">
                <div class="stat-card">
                    <h3 id="repoCount">0</h3>
                    <p>Repositories</p>
                </div>
                <div class="stat-card">
                    <h3 id="followerCount">0</h3>
                    <p>Followers</p>
                </div>
                <div class="stat-card">
                    <h3 id="followingCount">0</h3>
                    <p>Following</p>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section class="projects-section">
            <h2>Featured Projects</h2>
            <div class="projects-grid" id="projectsGrid">
                <!-- Projects will be loaded dynamically -->
            </div>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <p>© 2024 Sharan Appagoud. Built with ❤️</p>
        </footer>
    </div>

    <script src="script.js"></script>
</body>
</html>
