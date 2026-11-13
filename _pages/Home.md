
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
  --text: #26352b;
  color: var(--text);
  font-family: inherit;
}

.home-portfolio .hero {
  background: linear-gradient(135deg, #062b18 0%, #024115 65%, #08733a 100%);
  border-radius: 22px;
  padding: 55px 35px;
  color: #fff;
  margin: 10px 0 35px;
  position: relative;
  overflow: hidden;
}

.home-portfolio .hero:before {
  content: "";
  position: absolute;
  width: 300px;
  height: 300px;
  border: 1px solid rgba(255,255,255,.12);
  border-radius: 50%;
  right: -100px;
  top: -120px;
}

.home-portfolio .hero-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 35px;
  position: relative;
  z-index: 1;
}

.home-portfolio .hero-text {
  flex: 1 1 60%;
}

.home-portfolio .eyebrow {
  color: #e7c66e;
  text-transform: uppercase;
  letter-spacing: 3px;
  font-size: 12px;
  font-weight: 800;
}

.home-portfolio .hero h1 {
  color: #fff;
  font-size: clamp(34px, 5vw, 52px);
  line-height: 1.15;
  margin: 15px 0;
  font-weight: 850;
}

.home-portfolio .hero h2 {
  color: #e7c66e;
  font-size: 20px;
  line-height: 1.5;
  border: none;
  margin: 0 0 18px;
}

.home-portfolio .hero p {
  color: #e7eee9;
  font-size: 16px;
  line-height: 1.8;
  max-width: 650px;
}

.home-portfolio .profile-photo {
  flex: 0 0 230px;
  text-align: center;
}

.home-portfolio .profile-photo img {
  width: 220px;
  height: 220px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid var(--gold);
  box-shadow: 0 10px 35px rgba(0,0,0,.35);
}

.home-portfolio .hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 25px;
}

.home-portfolio .btn {
  display: inline-block;
  padding: 12px 22px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 800;
  font-size: 14px;
  transition: .2s ease;
}

.home-portfolio .btn-primary {
  background: var(--gold);
  color: #152b1b !important;
}

.home-portfolio .btn-outline {
  border: 1px solid #fff;
  color: #fff !important;
}

.home-portfolio .btn:hover {
  transform: translateY(-3px);
  opacity: .9;
}

.home-portfolio .section-heading {
  color: var(--green);
  font-size: 25px;
  font-weight: 850;
  margin: 42px 0 12px;
  border-bottom: 3px solid var(--gold);
  padding-bottom: 10px;
}

.home-portfolio .intro {
  font-size: 16px;
  line-height: 1.9;
}

.home-portfolio .highlight-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin: 25px 0;
}

.home-portfolio .highlight {
  background: var(--light);
  border: 1px solid #dce9df;
  border-top: 4px solid var(--green);
  padding: 22px;
  border-radius: 12px;
}

.home-portfolio .highlight .symbol {
  font-size: 27px;
  margin-bottom: 10px;
}

.home-portfolio .highlight h3 {
  color: var(--green);
  font-size: 17px;
  margin: 0 0 8px;
}

.home-portfolio .highlight p {
  font-size: 14px;
  line-height: 1.7;
  margin: 0;
}

.home-portfolio .skills {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 20px 0;
}

.home-portfolio .skill {
  background: #eaf2ec;
  color: var(--green);
  border: 1px solid #d4e3d7;
  padding: 8px 14px;
  border-radius: 30px;
  font-size: 13px;
  font-weight: 750;
}

.home-portfolio .project-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 18px;
  margin: 20px 0;
}

.home-portfolio .project {
  padding: 22px;
  border: 1px solid #e0e8e2;
  border-radius: 12px;
  background: #fff;
  box-shadow: 0 5px 18px rgba(0,0,0,.045);
}

.home-portfolio .project h3 {
  color: var(--green);
  font-size: 18px;
  margin-top: 0;
}

.home-portfolio .project p {
  font-size: 14px;
  line-height: 1.75;
}

.home-portfolio .project a {
  color: var(--green);
  font-weight: 800;
}

.home-portfolio .closing {
  background: var(--dark);
  color: white;
  padding: 35px 25px;
  border-radius: 15px;
  text-align: center;
  margin: 45px 0 15px;
}

.home-portfolio .closing h2 {
  color: #e7c66e;
  border: none;
  margin-top: 0;
}

.home-portfolio .closing p {
  color: #e6eee8;
}

@media (max-width: 700px) {
  .home-portfolio .hero {
    padding: 35px 22px;
  }

  .home-portfolio .hero-content {
    flex-direction: column-reverse;
    text-align: center;
  }

  .home-portfolio .profile-photo {
    flex-basis: auto;
  }

  .home-portfolio .profile-photo img {
    width: 175px;
    height: 175px;
  }

  .home-portfolio .hero-buttons {
    justify-content: center;
  }

  .home-portfolio .highlight-grid,
  .home-portfolio .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="home-portfolio">

  <section class="hero">
    <div class="hero-content">

      <div class="hero-text">
        <div class="eyebrow">Welcome to My Professional Portfolio</div>

        <h1>JANUARIES MULI</h1>

        <h2>ICT Professional | Web & Systems Developer | Cybersecurity Enthusiast</h2>

        <p>
          Transforming technology into practical solutions through innovation,
          digital systems, secure infrastructure and creative problem-solving.
          I am passionate about building reliable digital experiences that
          empower people, institutions and communities.
        </p>

        <div class="hero-buttons">
          <a class="btn btn-primary" href="/resume/">Explore My Resume</a>
          <a class="btn btn-outline" href="/projects/">View My Projects</a>
        </div>
      </div>

      <div class="profile-photo">
        <img src="/assets/images/januaries-muli.jpg"
             alt="Professional portrait of Januaries Muli">
      </div>

    </div>
  </section>

  <h2 class="section-heading">About Me</h2>

  <p class="intro">
    I am an ICT professional currently serving as the <strong>Diocesan ICT Technician
    at the Catholic Diocese of Maralal</strong>. My work involves managing ICT
    infrastructure, supporting digital transformation, developing web-based
    systems and maintaining reliable technology services.

    <br><br>

    I have a strong interest in web development, database management,
    cybersecurity, networking and information systems. I enjoy identifying
    technological challenges and developing solutions that improve efficiency,
    security and service delivery.
  </p>

  <h2 class="section-heading">What I Do</h2>

  <div class="highlight-grid">

    <div class="highlight">
      <div class="symbol">💻</div>
      <h3>Web Development</h3>
      <p>
        Designing and developing responsive websites, web applications
        and digital platforms using modern web technologies.
      </p>
    </div>

    <div class="highlight">
      <div class="symbol">🛡️</div>
      <h3>Cybersecurity</h3>
      <p>
        Exploring information security, vulnerability assessment,
        security analysis and responsible penetration testing in authorized labs.
      </p>
    </div>

    <div class="highlight">
      <div class="symbol">⚙️</div>
      <h3>ICT Infrastructure</h3>
      <p>
        Managing networks, servers, computers, CCTV, biometric systems
        and institutional ICT support services.
      </p>
    </div>

  </div>

  <h2 class="section-heading">Technical Skills</h2>

  <p>
    My technical interests and practical experience cover several areas of ICT:
  </p>

  <div class="skills">
    <span class="skill">HTML5</span>
    <span class="skill">CSS3</span>
    <span class="skill">JavaScript</span>
    <span class="skill">PHP</span>
    <span class="skill">MySQL</span>
    <span class="skill">Bootstrap</span>
    <span class="skill">WordPress</span>
    <span class="skill">Linux</span>
    <span class="skill">Cybersecurity</span>
    <span class="skill">Networking</span>
    <span class="skill">Database Management</span>
    <span class="skill">Git & GitHub</span>
    <span class="skill">CCTV Systems</span>
    <span class="skill">Server Administration</span>
  </div>

  <h2 class="section-heading">Featured Projects</h2>

  <div class="project-grid">

    <div class="project">
      <h3>🌐 Catholic Diocese of Maralal Website</h3>
      <p>
        Development and maintenance of a diocesan digital platform
        for communicating institutional information, events, news
        and services.
      </p>
      <a href="https://maralalcatholicdiocese.org/" target="_blank" rel="noopener">
        Visit Website →
      </a>
    </div>

    <div class="project">
      <h3>📻 Radio Mchungaji Website</h3>
      <p>
        Development of an online radio platform supporting digital
        broadcasting, programme information and listener engagement.
      </p>
      <a href="https://radiomchungaji.co.ke/" target="_blank" rel="noopener">
        Visit Website →
      </a>
    </div>

    <div class="project">
      <h3>📊 CDM ERP System</h3>
      <p>
        Development of a PHP and MySQL-based contributions management
        platform with collection records, allocation tracking,
        reporting and user access controls.
      </p>
      <a href="/projects/">Explore Project Details →</a>
    </div>

    <div class="project">
      <h3>🔐 Cybersecurity Lab Challenges</h3>
      <p>
        Practical security learning involving SQL injection testing,
        web application parameter discovery and Linux command-line
        enumeration in authorized training environments.
      </p>
      <a href="/labs/">Explore Lab Challenges →</a>
    </div>

  </div>

  <h2 class="section-heading">Professional Development</h2>

  <div class="highlight">
    <h3>Cyber Shujaa Programme – Security Analyst Track</h3>
    <p>
      <strong>United States International University-Africa (USIU-Africa)</strong>
      <br>
      August – December 2026
      <br><br>
      Currently undertaking professional cybersecurity training
      focused on security analysis, practical security skills and
      information security.
    </p>
  </div>

  <section class="closing">
    <h2>Let's Connect and Collaborate</h2>
    <p>
      I welcome opportunities to collaborate, exchange ideas and contribute
      to projects that use technology to create meaningful impact.
    </p>

    <div class="hero-buttons" style="justify-content:center;">
      <a class="btn btn-primary" href="/contact/">Contact Me</a>
      <a class="btn btn-outline" href="https://github.com/januariesmuli"
         target="_blank" rel="noopener">GitHub Profile</a>
    </div>
  </section>

</div>
