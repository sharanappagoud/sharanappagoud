<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Java Full Stack Developer Portfolio</title>

<style>
/* Google Font */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins', sans-serif;
}

body{
    background:linear-gradient(135deg,#0f172a,#1e293b,#334155);
    color:white;
    line-height:1.6;
}

/* Header Section */

header{
    text-align:center;
    padding:80px 20px;
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(10px);
    box-shadow:0 8px 32px rgba(0,0,0,0.3);
}

header h1{
    font-size:55px;
    color:#38bdf8;
    text-shadow:0 0 15px rgba(56,189,248,0.8);
    margin-bottom:10px;
}

header p{
    font-size:24px;
    color:#e2e8f0;
}

/* Sections */

section{
    width:85%;
    margin:60px auto;
}

/* Heading Style */

h2{
    font-size:32px;
    margin-bottom:25px;
    color:#38bdf8;
    position:relative;
    display:inline-block;
}

h2::after{
    content:'';
    position:absolute;
    width:60%;
    height:4px;
    background:#38bdf8;
    left:0;
    bottom:-8px;
    border-radius:10px;
}

/* About */

.about{
    background:rgba(255,255,255,0.05);
    padding:30px;
    border-radius:20px;
    box-shadow:0 8px 20px rgba(0,0,0,0.3);
}

/* Skills */

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
    gap:25px;
}

.card{
    background:rgba(255,255,255,0.08);
    padding:25px;
    border-radius:20px;
    text-align:center;
    font-size:20px;
    font-weight:600;
    transition:0.4s;
    cursor:pointer;
    box-shadow:0 8px 15px rgba(0,0,0,0.3);
}

.card:hover{
    transform:translateY(-10px) scale(1.05);
    background:#38bdf8;
    color:#0f172a;
    box-shadow:0 15px 30px rgba(56,189,248,0.5);
}

/* Projects */

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
}

.project-card{
    background:rgba(255,255,255,0.08);
    padding:30px;
    border-radius:20px;
    transition:0.4s;
    box-shadow:0 10px 20px rgba(0,0,0,0.3);
}

.project-card:hover{
    transform:translateY(-10px);
    box-shadow:0 20px 40px rgba(0,0,0,0.5);
}

.project-card h3{
    color:#38bdf8;
    margin-bottom:15px;
    font-size:24px;
}

.project-card p{
    color:#e2e8f0;
}

/* Buttons */

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:#38bdf8;
    color:#0f172a;
    text-decoration:none;
    border-radius:50px;
    font-weight:600;
    transition:0.3s;
}

.btn:hover{
    background:white;
    transform:scale(1.1);
}

/* Contact */

.contact{
    background:rgba(255,255,255,0.05);
    padding:30px;
    border-radius:20px;
    text-align:center;
}

.contact a{
    color:#38bdf8;
    text-decoration:none;
    font-weight:bold;
}

/* Footer */

footer{
    text-align:center;
    padding:25px;
    background:#020617;
    margin-top:50px;
    font-size:18px;
    color:#94a3b8;
}

/* Responsive */

@media(max-width:768px){

    header h1{
        font-size:40px;
    }

    header p{
        font-size:18px;
    }

    h2{
        font-size:28px;
    }

}


</style>
</head>

<body>

<header>
    <h1>Sharanappagoud</h1>
    <p>Java Full Stack Developer</p>
</header>

<section>
    <h2>About Me</h2>

    <p>
        Passionate Java Full Stack Developer with knowledge in Java,
        Spring Boot, Hibernate, JSP, Servlets, JDBC, and SQL databases.
        Interested in building responsive and scalable web applications.
    </p>
</section>

<section>

    <h2>Technical Skills</h2>

    <div class="skills">

        <div class="card">Java</div>
        <div class="card">JDBC</div>
        <div class="card">Servlets</div>
        <div class="card">JSP</div>
        <div class="card">Spring MVC</div>
        <div class="card">Spring Boot</div>
        <div class="card">Hibernate</div>
        <div class="card">HTML5</div>
        <div class="card">CSS3</div>
        <div class="card">JavaScript</div>
        <div class="card">MySQL</div>
        <div class="card">PostgreSQL</div>
        <div class="card">Git</div>
        <div class="card">GitHub</div>

    </div>

</section>

<section>

    <h2>Projects</h2>

    <div class="projects">

        <div class="project-card">

            <h3>Vehicle Service Management System</h3>

            <p>
                Developed a web application for booking mechanics,
                vehicle servicing, oil changes, and managing customer requests.
            </p>

            <a href="#" class="btn">View Project</a>

        </div>

        <div class="project-card">

            <h3>Student CRUD Application</h3>

            <p>
                Built a CRUD application using Spring MVC, Hibernate,
                JSP, and PostgreSQL database.
            </p>

            <a href="#" class="btn">View Project</a>

        </div>

    </div>

</section>

<section>

    <h2>Education</h2>

    <p>
        Bachelor Degree in Computer Science / Information Science
    </p>

</section>

<section>

    <h2>Contact</h2>

    <p>Email: sharanappagouda148@gmail.com</p>

    <p>
        GitHub:
        <a href="https://github.com/sharanappagoud" style="color:#38bdf8;">
            github.com/sharanappagoud
        </a>
    </p>

</section>

<footer>

    <p>© 2026 Sharanappagoud | Java Full Stack Developer</p>

</footer>

</body>
</html>
