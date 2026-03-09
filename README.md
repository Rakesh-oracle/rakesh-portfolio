<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rakesh Patro | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

html{
scroll-behavior:smooth;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif
}

body{
background:#f8fafc;
color:#1e293b;
transition:0.3s;
}

/* HEADER */

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:white;
box-shadow:0 5px 15px rgba(0,0,0,0.05);
position:sticky;
top:0;
z-index:1000
}

header h2{
color:#6366f1
}

nav a{
margin-left:20px;
text-decoration:none;
color:#1e293b;
font-weight:500
}

.dark-btn{
margin-left:20px;
padding:8px 14px;
border:none;
background:#6366f1;
color:white;
border-radius:6px;
cursor:pointer
}

/* HERO */

.hero{
display:flex;
align-items:center;
justify-content:space-between;
padding:80px 8%;
background:linear-gradient(120deg,#6366f1,#8b5cf6);
color:white
}

.hero-text h1{
font-size:3rem
}

.hero-text p{
margin:15px 0
}

.btn{
display:inline-block;
background:white;
color:#6366f1;
padding:12px 22px;
border-radius:8px;
text-decoration:none;
font-weight:600
}

.hero img{
width:280px;
border-radius:20px;
box-shadow:0 20px 40px rgba(0,0,0,0.3)
}

/* SECTIONS */

section{
padding:80px 8%
}

h2.section-title{
text-align:center;
margin-bottom:50px;
color:#6366f1
}

/* GRID */

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px
}

/* CARDS */

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 10px 30px rgba(0,0,0,0.08);
transition:0.3s
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 20px #6366f1
}

/* SKILLS */

.skills span{
display:inline-block;
background:#6366f1;
color:white;
padding:10px 15px;
border-radius:20px;
margin:8px 8px 0 0;
font-size:14px
}

.bar{
background:#e2e8f0;
border-radius:20px;
overflow:hidden;
margin:10px 0
}

.bar div{
height:12px;
background:#6366f1
}

.counter{
text-align:center;
font-size:2rem;
color:#6366f1;
font-weight:700
}

/* CONTACT */

.contact{
background:#63f1d2;
color:white;
text-align:center;
padding:60px 20px;
border-radius:20px
}

/* FOOTER */

footer{
text-align:center;
padding:25px;
background:#1e293b;
color:white
}

/* DARK MODE */

.dark{
background:#0f172a;
color:white
}

.dark header{
background:#020617
}

.dark .card{
background:#1e293b;
color:white
}

.dark nav a{
color:white
}

.dark .contact{
background:#14b8a6
}

</style>
</head>

<body>

<header>

<h2>Rakesh</h2>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#services">Services</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>

<button onclick="darkMode()" class="dark-btn">🌙</button>

</nav>

</header>

<section class="hero">

<div class="hero-text">

<h1>Hi, I'm Rakesh 👋</h1>

<p id="typing"></p>

<a href="G_Rakesh_Professional_Resume.pdf" class="btn" download>Download CV</a>

</div>

<img src="profile.png" alt="Rakesh">

</section>

<section id="about">

<h2 class="section-title">About Me</h2>

<div class="card">
Aspiring Python Developer passionate about backend development, automation, and building scalable applications using Python, Django, and SQL.

</div>

</section>

<section id="skills">

<h2 class="section-title">Skills & Experience</h2>

<div class="grid">

<div class="card">


<p>Python</p>
<div class="bar"><div style="width:90%"></div></div>

<p>Django</p>
<div class="bar"><div style="width:75%"></div></div>

<p>Flask</p>
<div class="bar"><div style="width:70%"></div></div>

<p>SQL / MySQL</p>
<div class="bar"><div style="width:80%"></div></div>

<p>REST API</p>
<div class="bar"><div style="width:40%"></div></div>

</div>

<div class="card">

<p class="counter">2</p>
<p style="text-align:center">Projects Completed</p>

<p class="counter">100+</p>
<p style="text-align:center">Hours of Coding</p>

</div>

</div>

</section>

<section id="services">

<h2 class="section-title">My Services</h2>

<div class="grid">

<div class="card">
<h3>Backend Development</h3>
<p>Building secure and scalable Java backend systems.</p>
</div>

<div class="card">
<h3>Database Design</h3>
<p>Designing optimized MySQL database structures.</p>
</div>

<div class="card">
<h3>API Development</h3>
<p>Creating REST APIs for applications.</p>
</div>

</div>

</section>

<section id="projects">

<h2 class="section-title">My Projects</h2>

<div class="grid">

<div class="card">
    <a href="https://"></a>
<h3>Employee Management System</h3>
<p>Python + MySQL CRUD system using JDBC connectivity.</p>
</div>

<div class="card">
<h3>Student Record System</h3>
<p>Backend application managing structured student data.</p>
</div>

</div>

</section>

<section id="contact">

<div class="contact">

<h2>Contact Us</h2>

<p>📧 : <a href="mailto:rakeshpatro7653@gmail.com">rakeshpatro7653@gmail.com</a></p>

<p>📞 : <a href="https://wa.me/917653813442">+91-7653813442</a></p>

<p>GitHub : <a href="https://github.com/Rakesh-oracle/rakesh-portfolio">GitHub Profile</a></p>

</div>

</section>

<footer>

© 2026 Rakesh Patro | Portfolio

</footer>

<script>

function darkMode(){
document.body.classList.toggle("dark");
}

/* Typing animation */

const text="Python Backend Developer | Django Learner | Building Smart Backend Systems";
let i=0;

function typing(){
if(i < text.length){
document.getElementById("typing").innerHTML += text.charAt(i);
i++;
setTimeout(typing,60);
}
}

typing();

</script>

</body>
</html>
