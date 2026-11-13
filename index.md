
---
layout: single
title: "Home"
permalink: /
author_profile: false
classes: wide
---

<style>
.home-portfolio {
  --green: #024115;
  --dark: #062b18;
  --gold: #c69b35;
  --light: #f0f6f1;
  color: #26352b;
  line-height: 1.75;
}

.home-portfolio .hero {
  background: linear-gradient(135deg, #062b18, #07552b);
  color: white;
  padding: 45px 30px;
  border-radius: 18px;
  border-bottom: 5px solid var(--gold);
  margin: 20px 0 35px;
}

.home-portfolio .hero-inner {
  display: flex;
  align-items: center;
  gap: 35px;
}

.home-portfolio .hero-text {
  flex: 1;
}

.home-portfolio .eyebrow {
  color: #e7c66e;
  letter-spacing: 2px;
  font-size: 12px;
  font-weight: bold;
}

.home-portfolio .hero h1 {
  color: white;
  font-size: clamp(34px, 5vw, 52px);
  margin: 12px 0;
  border: none;
}

.home-portfolio .hero h2 {
  color: #e7c66e;
  font-size: 19px;
  border: none;
}

.home-portfolio .hero p {
  color: #e8f2e9;
}

.home-portfolio .photo {
  flex: 0 0 210px;
  text-align: center;
}

.home-portfolio .photo img {
  width: 205px;
  height: 205px;
  object-fit: cover;
  border-radius: 50%;
  border: 5px solid var(--gold);
}

.home-portfolio .btn {
  display: inline-block;
  padding: 11px 20px;
  margin: 8px 7px 0 0;
  border-radius: 7px;
  background: var(--gold);
  color: #102316 !important;
  font-weight: bold;
  text-decoration: none;
}

.home-portfolio .btn-outline {
  background: transparent;
  border: 1px solid white;
  color: white !important;
}

.home-portfolio .section-title {
  color: var(--green);
  border-bottom: 2px solid var(--gold);
  padding-bottom: 9px;
  margin: 38px 0 20px;
}

.home-portfolio .cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
  margin: 22px 0;
}

.home-portfolio .card {
  background: var(--light);
  border: 1px solid #dce8df;
  border-top: 4px solid var(--green);
  border-radius: 12px;
  padding: 21px;
}

.home-portfolio .card h3 {
  color: var(--green);
  margin-top: 5px;
  border: none;
}

.home-portfolio .card p {
  font-size: 14px;
}

.home-portfolio .skills {
  display: flex;
  flex-wrap: wrap;
  gap: 9px;
}

.home-portfolio .skills span {
  background: var(--light);
  color: var(--green);
  border: 1px solid #c9dfcc;
  border-radius: 20px;
  padding: 7px 13px;
  font-size: 13px;
  font-weight: bold;
}

.home-portfolio .closing {
  background: var(--dark);
  color: white;
  text-align: center;
  padding: 32px 20px;
  border-radius: 14px;
  margin-top: 40px;
}

.home-portfolio .closing h2 {
  color: #e7c66e;
  border: none;
}

@media(max-width:650px) {
  .home-portfolio .hero-inner {
    flex-direction: column-reverse;
    text-align: center;
  }

  .home-portfolio .photo img {
    width: 165px;
    height: 165px;
  }
}
</style>

<div class="home-portfolio">

<section class="hero">
  <div class="hero-inner">

    <div class="hero-text">
      <div class="eyebrow">WELCOME TO MY PROFESSIONAL PORTFOLIO</div>

      <h1>JANUARIES MULI</h1>

      <h2>ICT Professional | Web & Systems Developer | Cybersecurity Enthusiast</h2>

      <p>
        Transforming technology into practical solutions through innovation,
        digital systems, secure infrastructure and creative problem-solving.
        Passionate about building reliable digital experiences that empower
        institutions and communities.
      </p>

      <a class="btn" href="/resume/">Explore My Resume →</a>
      <a class="btn btn-outline" href="/projects/">View My Projects →</a>
    </div>

    <div class="photo">
      <img src="/assets/images/januaries.jpeg"
           alt="Professional photograph of Januaries Muli">
    </div>

  </div>
</section>

<h2 class="section-title">About Me</h2>

<p>
I am an ICT professional serving as the <strong>Diocesan ICT Technician
at the Catholic Diocese of Maralal</strong>. I work in ICT infrastructure
management, technical support, systems development, web technologies
and digital transformation.
</p>

<p>
My interests include cybersecurity, database management, networking,
web application development and the use of technology to solve
real-world institutional challenges.
</p>

<h2 class="section-title">Areas of Expertise</h2>

<div class="cards">

  <div class="card">
    <h3>💻 Web Development</h3>
    <p>Building responsive websites, web applications and digital platforms.</p>
  </div>

  <div class="card">
    <h3>🛡️ Cybersecurity</h3>
    <p>Security analysis, vulnerability assessment and authorized security testing.</p>
  </div>

  <div class="card">
    <h3>🌐 Networking & Infrastructure</h3>
    <p>Network administration, servers, CCTV, biometrics and ICT infrastructure.</p>
  </div>

  <div class="card">
    <h3>⚙️ Systems Development</h3>
    <p>Developing database-driven applications and institutional management systems.</p>
  </div>

</div>

<h2 class="section-title">Technical Skills</h2>

<div class="skills">
  <span>HTML5</span>
  <span>CSS3</span>
  <span>JavaScript</span>
  <span>PHP</span>
  <span>MySQL</span>
  <span>Bootstrap</span>
  <span>WordPress</span>
  <span>Linux</span>
  <span>Kali Linux</span>
  <span>SQLMap</span>
  <span>Git & GitHub</span>
  <span>Networking</span>
  <span>Database Management</span>
  <span>Server Administration</span>
</div>

<h2 class="section-title">Featured Projects</h2>

<div class="cards">

  <div class="card">
    <h3>🌐 Catholic Diocese of Maralal</h3>
    <p>Development and maintenance of the diocesan website and digital communication platform.</p>
    <a href="https://maralalcatholicdiocese.org/">Visit Website →</a>
  </div>

  <div class="card">
    <h3>📻 Radio Mchungaji</h3>
    <p>Online radio website supporting digital broadcasting and Catholic evangelization.</p>
    <a href="https://radiomchungaji.co.ke/">Visit Website →</a>
  </div>

  <div class="card">
    <h3>📊 CDM ERP</h3>
    <p>PHP and MySQL contributions management system for diocesan and parish records.</p>
    <a href="/projects/">Explore Projects →</a>
  </div>

  <div class="card">
    <h3>🔐 Cybersecurity Labs</h3>
    <p>Practical security exercises involving SQL injection, web testing and Linux enumeration.</p>
    <a href="/labs/">Explore Labs →</a>
  </div>

</div>

<h2 class="section-title">Professional Development</h2>

<div class="card">
  <h3>Cyber Shujaa Programme – Security Analyst Track</h3>
  <p>
    <strong>USIU-Africa | August – December 2026</strong>
  </p>
  <p>
    Currently undertaking cybersecurity training focused on security
    analysis, practical cybersecurity skills and information security.
  </p>
</div>

<section class="closing">
  <h2>Let's Connect and Collaborate</h2>
  <p>
    Interested in ICT, systems development, cybersecurity or digital
    transformation? Let's connect and explore opportunities to work together.
  </p>
  <a class="btn" href="/contact/">Contact Me →</a>
  <a class="btn btn-outline"
     href="https://github.com/januariesmuli"
     target="_blank" rel="noopener">GitHub Profile</a>
</section>

</div>
