<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Alaparthi Hema Venkata Krishna Teja — Portfolio</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#ffffff; --text:#0b0b0b; --muted:#6b7280; --accent:#0f766e; --card:#f8fafb;
      --radius:14px; --gap:28px; --maxw:980px;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui;background:var(--bg);color:var(--text)}
    .wrap{max-width:var(--maxw);margin:40px auto;padding:30px;border-radius:20px;box-shadow:0 8px 30px rgba(0,0,0,0.06)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:var(--gap)}

    header{display:flex;justify-content:space-between;margin-bottom:20px}
    .brand{display:flex;gap:16px;align-items:center}
    .avatar{width:70px;height:70px;border-radius:12px;background:var(--accent);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:700}
    h1{margin:0}
    .lead{color:var(--muted)}

    .card{background:var(--card);padding:18px;border-radius:12px;margin-bottom:16px}
    .muted{color:var(--muted);font-size:14px}

    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .chip{background:#fff;padding:6px 10px;border-radius:20px;border:1px solid #eee;font-size:13px}

    .project{margin-bottom:10px}
    .project h4{margin:0}

    aside .item{margin-bottom:12px}

    a{color:var(--accent);text-decoration:none}

    @media(max-width:900px){
      .grid{grid-template-columns:1fr}
    }
  </style>
</head>

<body>
<main class="wrap">

<header>
  <div class="brand">
    <div class="avatar">AH</div>
    <div>
      <h1>Alaparthi Hema Venkata Krishna Teja</h1>
      <div class="lead">M.Tech (ECE) — Micro Electronic System Design</div>
    </div>
  </div>
  <div class="muted">ID: RA2412705010005</div>
</header>

<div class="grid">

<section>

<div class="card">
<h3>About Me</h3>
<p class="muted">
2nd-year M.Tech student in Electronics and Communication Engineering with strong interest in microelectronics, VLSI, and embedded systems. Passionate about building real-world hardware solutions and integrating software with electronics.
</p>
</div>

<div class="card">
<h3>Skills</h3>
<div class="skills">
<div class="chip">Python</div>
<div class="chip">C (Basics)</div>
<div class="chip">Microelectronics</div>
<div class="chip">VLSI</div>
<div class="chip">Embedded Systems</div>
<div class="chip">Circuit Design</div>
</div>
</div>

<div class="card">
<h3>Projects</h3>

<div class="project">
<h4>Fire Detecting Machine</h4>
<p class="muted">Sensor-based system for early fire detection and alert generation.</p>
</div>

<div class="project">
<h4>Mobile Jammer</h4>
<p class="muted">Controlled-range mobile signal jammer using RF concepts.</p>
</div>

<div class="project">
<h4>Traffic Light Controller using 555 Timer</h4>
<p class="muted">Designed a traffic signal system using 555 timer IC for sequential light control.</p>
</div>

</div>

<div class="card">
<h3>Certifications</h3>
<ul class="muted">
<li>
Critical Thinking: Change Your Perspective and Think Smarter  
<br>
<a href="https://www.udemy.com/certificate/UC-f1fe7447-6d4c-48c5-bb78-2d8c2ee48d6d/" target="_blank">View Certificate</a>
</li>
</ul>
</div>

<div class="card">
<h3>Hackathon & Activities</h3>
<ul class="muted">
<li>Participated in Clash of Minds Hackathon</li>
<li>Active in technical events and team-based problem solving</li>
</ul>
</div>

<div class="card">
<h3>Achievements</h3>
<ul class="muted">
<li>Completed VLSI Internship (June 2025 – July 2025)</li>
<li>Built multiple hardware prototypes</li>
</ul>
</div>

</section>

<aside>

<div class="card">
<div class="item">
<b>Email</b><br>
<a href="mailto:ha5966@srmist.edu.in">ha5966@srmist.edu.in</a>
</div>

<div class="item">
<b>Phone</b><br>
<a href="tel:+918985675123">+91 8985675123</a>
</div>

<div class="item">
<b>LinkedIn</b><br>
<a href="https://www.linkedin.com/in/krishna-teja-alaparthi-45485b324" target="_blank">Profile</a>
</div>

<div class="item">
<b>Location</b><br>
Chennai, India
</div>

<div class="item">
<b>Education</b><br>
M.Tech ECE (2nd Year)
</div>

</div>

</aside>

</div>

<footer class="muted" style="margin-top:20px;text-align:center">
© 2025 Alaparthi Hema Venkata Krishna Teja
</footer>

</main>
</body>
</html>
