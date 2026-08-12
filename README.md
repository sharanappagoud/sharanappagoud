<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sharanappagouda | Java Full Stack Developer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:            #1a1b26;
    --surface:       #20222f;
    --surface-2:     #24273a;
    --border:        #33364d;
    --text:          #c0caf5;
    --text-dim:      #7a80a8;
    --comment:       #565f89;
    --blue:          #7dcfff;   /* keywords */
    --green:         #9ece6a;   /* strings */
    --gold:          #e0af68;   /* methods / accents */
    --pink:          #bb9af7;   /* class names */
    --mono: 'JetBrains Mono', 'Courier New', monospace;
    --sans: 'Inter', -apple-system, sans-serif;
  }

  *{ box-sizing:border-box; }

  body{
    margin:0;
    background:
      radial-gradient(ellipse at top, #1f2137 0%, var(--bg) 55%);
    color:var(--text);
    font-family:var(--sans);
    line-height:1.65;
    -webkit-font-smoothing:antialiased;
  }

  /* ---------- HEADER : rendered as a class declaration ---------- */
  header{
    position:relative;
    padding:4.5rem 2rem 3.5rem;
    text-align:left;
    max-width:820px;
    margin:0 auto;
    border-bottom:1px solid var(--border);
  }
  header::before{
    content:"// portfolio.java";
    display:block;
    font-family:var(--mono);
    font-size:0.85rem;
    color:var(--comment);
    margin-bottom:1.75rem;
  }
  header h1{
    font-family:var(--mono);
    font-weight:800;
    font-size:clamp(1.6rem, 4vw, 2.5rem);
    margin:0;
    letter-spacing:-0.5px;
  }
  header h1 .kw{ color:var(--blue); }
  header h1 .cls{ color:var(--pink); }
  header h1 .brace{ color:var(--text-dim); }
  header p{
    font-family:var(--mono);
    font-size:1rem;
    margin:0.9rem 0 0 1.6rem;
    color:var(--text-dim);
  }
  header p .prop{ color:var(--gold); }
  header p .str{ color:var(--green); }
  header p::after{
    content:"";
    display:inline-block;
    width:9px; height:1.1em;
    margin-left:6px;
    background:var(--blue);
    vertical-align:text-bottom;
    animation:blink 1.1s steps(1) infinite;
  }
  @keyframes blink{ 50%{ opacity:0; } }

  /* ---------- SECTIONS ---------- */
  section{
    max-width:820px;
    margin:0 auto;
    padding:3rem 2rem;
    border-bottom:1px solid var(--border);
  }
  section h2{
    font-family:var(--mono);
    font-size:0.95rem;
    font-weight:500;
    color:var(--comment);
    text-transform:none;
    letter-spacing:0.3px;
    margin:0 0 1.5rem;
  }
  section h2::before{ content:"// "; color:var(--comment); }

  section p{
    color:var(--text);
    font-size:1.02rem;
    max-width:70ch;
  }

  /* ---------- SKILLS : styled like import tokens ---------- */
  .skills{
    display:flex;
    flex-wrap:wrap;
    gap:0.6rem;
  }
  .card{
    font-family:var(--mono);
    font-size:0.85rem;
    color:var(--blue);
    background:var(--surface-2);
    border:1px solid var(--border);
    border-radius:5px;
    padding:0.45rem 0.85rem;
    transition:border-color 0.15s ease, transform 0.15s ease;
  }
  .card:hover{
    border-color:var(--blue);
    transform:translateY(-2px);
  }
  .card::before{ content:"import "; color:var(--comment); }

  /* ---------- PROJECTS ---------- */
  .projects{
    display:flex;
    flex-direction:column;
    gap:1.5rem;
  }
  .project-card{
    background:var(--surface);
    border:1px solid var(--border);
    border-left:3px solid var(--green);
    border-radius:6px;
    padding:1.75rem;
  }
  .project-card h3{
    font-family:var(--mono);
    font-size:1.1rem;
    color:var(--pink);
    margin:0 0 0.9rem;
  }
  .project-card p{
    color:var(--text-dim);
    font-size:0.95rem;
    white-space:pre-line;
    margin:0 0 1.25rem;
  }
  .btn{
    display:inline-flex;
    align-items:center;
    gap:0.5rem;
    font-family:var(--mono);
    font-size:0.85rem;
    color:var(--bg);
    background:var(--gold);
    text-decoration:none;
    padding:0.55rem 1.1rem;
    border-radius:5px;
    font-weight:700;
    transition:filter 0.15s ease;
  }
  .btn::before{ content:"→"; }
  .btn:hover{ filter:brightness(1.12); }

  /* ---------- CONTACT / FOOTER ---------- */
  section a{
    color:var(--blue);
    text-decoration:none;
    border-bottom:1px solid transparent;
  }
  section a:hover{ border-bottom-color:var(--blue); }

  footer{
    max-width:820px;
    margin:0 auto;
    padding:2rem;
    text-align:center;
    font-family:var(--mono);
    font-size:0.8rem;
    color:var(--comment);
  }

  @media (max-width:600px){
    header, section, footer{ padding-left:1.25rem; padding-right:1.25rem; }
    header{ padding-top:3rem; }
  }
</style>
</head>
<body>

<header>
    <h1><span class="kw">public class</span> <span class="cls">Sharanappagouda</span> <span class="brace">{</span></h1>
    <p><span class="prop">String</span> role = <span class="str">"Java Full Stack Developer"</span>;</p>
</header>

<section>
    <h2>About Me</h2>
    <p>
        Recent Bachelor of Engineering graduate in Artificial Intelligence and Data Science with strong knowledge of Java, Spring Boot, Spring MVC,
Hibernate, REST APIs, MySQL, HTML, CSS, JavaScript, and Git. Hands-on experience building full-stack and REST API-based applications
through academic and personal projects, including CRUD operations, database integration, and MVC architecture. Proficient in object-
oriented programming, data structures, SQL, and software development best practices. Seeking a Java Backend or Full Stack Developer role
to apply hands-on experience in Spring Boot, REST APIs, and database-driven application development.
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
            <h3>Employee Management System (REST API)</h3>
            <p>Tech Stack: Java, Spring Boot, Hibernate, MySQL, Thymeleaf
• Developed a full-stack stock market simulation application using Spring Boot, Thymeleaf, Hibernate, and MySQL.
• Integrated Alpha Vantage API for real-time stock price updates.
• Implemented secure OTP-based email verification, wallet management, and portfolio tracking.
• Built stock buy/sell functionality with profit and loss analysis.
• Designed role-based access for Admin and User using MVC architecture.</p>
            <a href="https://github.com/sharanappagoud/EmployeeManagementSystem-REST-API-" class="btn">View Project</a>
        </div>
        <div class="project-card">
            <h3>NammaStock – Stock Market Simulation Application</h3>
            <p>Tech Stack: Java, Spring Boot, Hibernate, MySQL, Thymeleaf
• Developed a full-stack stock market simulation application using Spring Boot, Thymeleaf, Hibernate, and MySQL.
• Integrated Alpha Vantage API for real-time stock price updates.
• Implemented secure OTP-based email verification, wallet management, and portfolio tracking.
• Built stock buy/sell functionality with profit and loss analysis.
• Designed role-based access for Admin and User using MVC architecture.</p>
            <a href="https://github.com/sharanappagoud/stock-market-springboot-thymeleaf-master" class="btn">View Project</a>
        </div>
    </div>
</section>

<section>
    <h2>Education</h2>
    <p>
        Bachelor of Engineering (B.E.) in Artificial Intelligence and Data Science<br>
        Government Engineering College, Nargund<br>
        CGPA: 8.1/10
    </p>
</section>

<section>
    <h2>Contact</h2>
    <p>Email: <a href="mailto:sharanappagouda148@gmail.com">sharanappagouda148@gmail.com</a></p>
    <p>
        GitHub:
        <a href="https://github.com/sharanappagoud" target="_blank" rel="noopener">
            github.com/sharanappagoud
        </a>
    </p>
</section>

<footer>
    <p>© 2026 Sharanappagoud | Java Full Stack Developer</p>
</footer>

</body>
</html>
