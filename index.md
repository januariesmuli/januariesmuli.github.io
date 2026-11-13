---
layout: single
title: "Home"
permalink: /
author_profile: false
classes: wide
---

<style>
/* =========================================
   JANUARIES MULI - PROFESSIONAL PORTFOLIO
========================================= */

:root {
  --pm-green: #024115;
  --pm-dark: #062b18;
  --pm-deep: #031b10;
  --pm-gold: #c69b35;
  --pm-light: #f0f6f1;
  --pm-white: #ffffff;
  --pm-text: #26352b;
  --pm-muted: #66756b;
}

.portfolio-home {
  width: 100%;
  max-width: 1500px;
  margin: 0 auto;
  color: var(--pm-text);
  font-family: inherit;
  overflow: hidden;
}

.portfolio-home * {
  box-sizing: border-box;
}

.portfolio-home a {
  text-decoration: none;
}

.portfolio-home .section-wrap {
  padding: 85px 6%;
}

.portfolio-home .section-heading {
  text-align: center;
  margin-bottom: 48px;
}

.portfolio-home .section-heading span {
  display: inline-block;
  color: var(--pm-green);
  background: #e5f0e7;
  border-radius: 30px;
  padding: 7px 17px;
  font-size: 12px;
  font-weight: 800;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.portfolio-home .section-heading h2 {
  color: var(--pm-dark);
  font-size: clamp(27px, 4vw, 42px);
  font-weight: 850;
  margin: 15px 0 12px;
  letter-spacing: -1px;
}

.portfolio-home .section-heading p {
  max-width: 680px;
  margin: 0 auto;
  color: var(--pm-muted);
  font-size: 16px;
  line-height: 1.8;
}

/* HERO */

.portfolio-home .hero {
  position: relative;
  min-height: 690px;
  display: flex;
  align-items: center;
  padding: 75px 7%;
  border-radius: 0 0 30px 30px;
  overflow: hidden;
  color: white;
  background:
    radial-gradient(circle at 80% 20%, rgba(198,155,53,.20), transparent 28%),
    radial-gradient(circle at 15% 85%, rgba(18,119,57,.35), transparent 30%),
    linear-gradient(125deg, #031b10 0%, #062b18 50%, #07552b 100%);
}

.portfolio-home .hero:before {
  content: "";
  position: absolute;
  width: 430px;
  height: 430px;
  border: 1px solid rgba(255,255,255,.12);
  border-radius: 50%;
  right: -100px;
  top: -100px;
  box-shadow: 0 0 0 55px rgba(255,255,255,.025),
              0 0 0 110px rgba(255,255,255,.02);
}

.portfolio-home .hero:after {
  content: "";
  position: absolute;
  width: 240px;
  height: 240px;
  border-radius: 50%;
  background: rgba(198,155,53,.10);
  bottom: -120px;
  left: 35%;
  filter: blur(8px);
}

.portfolio-home .hero-inner {
  position: relative;
  z-index: 2;
  width: 100%;
  max-width: 1250px;
  margin: auto;
  display: grid;
  grid-template-columns: 1.35fr .8fr;
  gap: 65px;
  align-items: center;
}

.portfolio-home .hero-label {
  color: #e7c66f;
  font-size: 13px;
  font-weight: 800;
  letter-spacing: 3px;
  text-transform: uppercase;
  margin-bottom: 20px;
}

.portfolio-home .hero h1 {
  color: white;
  font-size: clamp(43px, 6vw, 76px);
  line-height: 1.05;
  font-weight: 900;
  letter-spacing: -2.5px;
  margin: 0 0 22px;
}

.portfolio-home .hero h1 em {
  color: var(--pm-gold);
  font-style: normal;
}

.portfolio-home .hero h2 {
  color: #e5eee7;
  font-size: clamp(18px, 2.2vw, 25px);
  font-weight: 500;
  line-height: 1.5;
  margin: 0 0 20px;
}

.portfolio-home .hero-description {
  max-width: 650px;
  color: #d0ded4;
  font-size: 16px;
  line-height: 1.9;
  margin-bottom: 32px;
}

.portfolio-home .hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-bottom: 30px;
}

.portfolio-home .btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 9px;
  padding: 14px 24px;
  border-radius: 8px;
  font-weight: 800;
  font-size: 14px;
  transition: .25s ease;
}

.portfolio-home .btn-gold {
  background: var(--pm-gold);
  color: #102415 !important;
}

.portfolio-home .btn-gold:hover {
  background: #e1b94e;
  transform: translateY(-4px);
  box-shadow: 0 12px 25px rgba(0,0,0,.2);
}

.portfolio-home .btn-outline {
  color: white !important;
  border: 1px solid rgba(255,255,255,.55);
}

.portfolio-home .btn-outline:hover {
  background: white;
  color: var(--pm-dark) !important;
  transform: translateY(-4px);
}

.portfolio-home .hero-socials {
  display: flex;
  flex-wrap: wrap;
  gap: 22px;
}

.portfolio-home .hero-socials a {
  color: #e5eee7;
  font-size: 13px;
  font-weight: 700;
}

.portfolio-home .hero-socials a:hover {
  color: var(--pm-gold);
}

/* PROFILE IMAGE */

.portfolio-home .profile-visual {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.portfolio-home .profile-ring {
  width: min(360px, 100%);
  aspect-ratio: 1;
  border-radius: 50%;
  padding: 11px;
  border: 2px solid rgba(198,155,53,.8);
  background: rgba(255,255,255,.06);
  box-shadow: 0 25px 65px rgba(0,0,0,.35);
}

.portfolio-home .profile-ring img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
  object-position: center;
  border-radius: 50%;
  border: 5px solid rgba(255,255,255,.12);
}

.portfolio-home .profile-caption {
  position: absolute;
  bottom: 8px;
  left: 0;
  background: white;
  color: var(--pm-dark);
  padding: 13px 19px;
  border-left: 4px solid var(--pm-gold);
  border-radius: 7px;
  box-shadow: 0 12px 30px rgba(0,0,0,.2);
  font-size: 13px;
  font-weight: 800;
}

.portfolio-home .profile-caption small {
  display: block;
  color: var(--pm-muted);
  font-size: 11px;
  font-weight: 500;
  margin-top: 3px;
}

/* QUICK FACTS */

.portfolio-home .quick-facts {
  position: relative;
  z-index: 3;
  width: 88%;
  max-width: 1120px;
  margin: -35px auto 0;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  background: white;
  border-radius: 15px;
  box-shadow: 0 15px 45px rgba(0,0,0,.10);
  padding: 28px 15px;
}

.portfolio-home .fact {
  text-align: center;
  padding: 10px;
  border-right: 1px solid #e5ece6;
}

.portfolio-home .fact:last-child {
  border-right: none;
}

.portfolio-home .fact strong {
  display: block;
  color: var(--pm-green);
  font-size: 25px;
  font-weight: 900;
}

.portfolio-home .fact span {
  color: var(--pm-muted);
  font-size: 12px;
  font-weight: 700;
}

/* ABOUT */

.portfolio-home .about-grid {
  display: grid;
  grid-template-columns: 1.1fr .9fr;
  gap: 55px;
  align-items: center;
}

.portfolio-home .about-copy h3 {
  color: var(--pm-dark);
  font-size: 27px;
  margin: 0 0 18px;
}

.portfolio-home .about-copy p {
  color: var(--pm-muted);
  font-size: 15px;
  line-height: 1.95;
  margin-bottom: 17px;
}

.portfolio-home .about-highlight {
  background: var(--pm-light);
  border-left: 5px solid var(--pm-gold);
  border-radius: 9px;
  padding: 24px;
  margin-top: 24px;
  color: var(--pm-dark);
  font-weight: 650;
  line-height: 1.8;
}

.portfolio-home .about-cards {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 17px;
}

.portfolio-home .about-card {
  background: white;
  border: 1px solid #e5ece6;
  border-radius: 13px;
  padding: 25px 20px;
  transition: .25s ease;
  box-shadow: 0 8px 25px rgba(0,0,0,.035);
}

.portfolio-home .about-card:hover {
  transform: translateY(-7px);
  border-color: var(--pm-gold);
  box-shadow: 0 15px 30px rgba(2,65,21,.09);
}

.portfolio-home .about-card .symbol {
  font-size: 28px;
  margin-bottom: 13px;
}

.portfolio-home .about-card h4 {
  color: var(--pm-green);
  font-size: 16px;
  margin: 0 0 9px;
}

.portfolio-home .about-card p {
  color: var(--pm-muted);
  font-size: 13px;
  line-height: 1.7;
  margin: 0;
}

/* EXPERTISE */

.portfolio-home .expertise-section {
  background: var(--pm-light);
}

.portfolio-home .expertise-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
}

.portfolio-home .expertise-card {
  background: white;
  padding: 30px 26px;
  border-radius: 13px;
  border-bottom: 4px solid transparent;
  box-shadow: 0 8px 25px rgba(0,0,0,.035);
  transition: .3s ease;
}

.portfolio-home .expertise-card:hover {
  transform: translateY(-8px);
  border-bottom-color: var(--pm-gold);
  box-shadow: 0 17px 35px rgba(2,65,21,.10);
}

.portfolio-home .expertise-card .symbol {
  width: 53px;
  height: 53px;
  border-radius: 12px;
  display: grid;
  place-items: center;
  background: #e7f1e9;
  font-size: 25px;
  margin-bottom: 19px;
}

.portfolio-home .expertise-card h3 {
  color: var(--pm-dark);
  font-size: 18px;
  margin: 0 0 12px;
}

.portfolio-home .expertise-card p {
  color: var(--pm-muted);
  font-size: 14px;
  line-height: 1.8;
  margin: 0;
}

/* SKILLS */

.portfolio-home .skills-layout {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 35px;
}

.portfolio-home .skill-group {
  background: white;
  border: 1px solid #e6ece7;
  border-radius: 13px;
  padding: 28px;
}

.portfolio-home .skill-group h3 {
  color: var(--pm-green);
  margin: 0 0 22px;
  font-size: 19px;
}

.portfolio-home .skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.portfolio-home .skill-tags span {
  display: inline-block;
  background: #edf4ee;
  color: var(--pm-green);
  padding: 9px 13px;
  border-radius: 6px;
  font-size: 12px;
  font-weight: 750;
  transition: .2s ease;
}

.portfolio-home .skill-tags span:hover {
  background: var(--pm-green);
  color: white;
  transform: translateY(-3px);
}

/* PROJECTS */

.portfolio-home .projects-section {
  background: #f8faf8;
}

.portfolio-home .projects-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 24px;
}

.portfolio-home .project-card {
  background: white;
  border: 1px solid #e5ece6;
  border-radius: 14px;
  overflow: hidden;
  box-shadow: 0 8px 25px rgba(0,0,0,.04);
  transition: .3s ease;
}

.portfolio-home .project-card:hover {
  transform: translateY(-7px);
  box-shadow: 0 18px 38px rgba(2,65,21,.11);
}

.portfolio-home .project-top {
  padding: 24px 27px;
  background: linear-gradient(120deg, #062b18, #07552b);
  color: white;
}

.portfolio-home .project-top span {
  color: #e7c66f;
  font-size: 11px;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: 1.5px;
}

.portfolio-home .project-top h3 {
  color: white;
  font-size: 20px;
  margin: 10px 0 0;
}

.portfolio-home .project-body {
  padding: 24px 27px;
}

.portfolio-home .project-body p {
  color: var(--pm-muted);
  font-size: 14px;
  line-height: 1.8;
}

.portfolio-home .project-body details {
  border-top: 1px solid #e7ede8;
  padding-top: 14px;
  margin-top: 15px;
}

.portfolio-home .project-body summary {
  color: var(--pm-green);
  cursor: pointer;
  font-size: 13px;
  font-weight: 800;
  list-style-position: inside;
}

.portfolio-home .project-body details p {
  margin-top: 13px;
}

.portfolio-home .project-link {
  display: inline-block;
  color: var(--pm-green);
  font-size: 13px;
  font-weight: 800;
  margin-top: 10px;
}

.portfolio-home .project-link:hover {
  color: #a77a16;
}

/* PROFESSIONAL DEVELOPMENT */

.portfolio-home .training-panel {
  background: linear-gradient(120deg, #062b18, #07552b);
  color: white;
  border-radius: 18px;
  padding: 42px;
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 25px;
  align-items: center;
  box-shadow: 0 15px 40px rgba(2,65,21,.15);
}

.portfolio-home .training-panel .eyebrow {
  color: #e7c66f;
  font-size: 12px;
  font-weight: 800;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.portfolio-home .training-panel h3 {
  color: white;
  font-size: 25px;
  margin: 12px 0;
}

.portfolio-home .training-panel p {
  color: #d4e3d8;
  font-size: 14px;
  line-height: 1.8;
  margin: 0;
}

.portfolio-home .training-badge {
  border: 1px solid rgba(255,255,255,.35);
  border-radius: 12px;
  padding: 18px 23px;
  color: #f0d17b;
  font-size: 13px;
  font-weight: 800;
  text-align: center;
}

/* CONTACT */

.portfolio-home .contact-section {
  background: var(--pm-light);
}

.portfolio-home .contact-panel {
  max-width: 950px;
  margin: auto;
  text-align: center;
  background: white;
  border-radius: 18px;
  padding: 55px 30px;
  box-shadow: 0 12px 35px rgba(0,0,0,.06);
}

.portfolio-home .contact-panel h2 {
  color: var(--pm-dark);
  font-size: clamp(27px, 4vw, 39px);
  margin: 0 0 15px;
}

.portfolio-home .contact-panel p {
  color: var(--pm-muted);
  max-width: 650px;
  margin: 0 auto 27px;
  line-height: 1.8;
}

.portfolio-home .contact-details {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 13px;
  margin: 25px 0;
}

.portfolio-home .contact-details a {
  background: #edf4ee;
  color: var(--pm-green);
  padding: 12px 16px;
  border-radius: 7px;
  font-size: 13px;
  font-weight: 750;
}

.portfolio-home .contact-details a:hover {
  background: var(--pm-green);
  color: white;
}

/* FOOTER */

.portfolio-home .portfolio-footer {
  background: var(--pm-deep);
  color: #d2dfd5;
  text-align: center;
  padding: 28px 15px;
  font-size: 13px;
}

.portfolio-home .portfolio-footer strong {
  color: #e7c66f;
}

/* ANIMATIONS */

@keyframes pmFadeUp {
  from { opacity: 0; transform: translateY(22px); }
  to { opacity: 1; transform: translateY(0); }
}

.portfolio-home .hero-copy {
  animation: pmFadeUp .8s ease both;
}

.portfolio-home .profile-visual {
  animation: pmFadeUp 1s ease both;
}

/* RESPONSIVE DESIGN */

@media (max-width: 900px) {
  .portfolio-home .hero-inner {
    grid-template-columns: 1fr .75fr;
    gap: 25px;
  }

  .portfolio-home .hero {
    min-height: 600px;
    padding: 65px 5%;
  }

  .portfolio-home .expertise-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 650px) {
  .portfolio-home .hero {
    min-height: auto;
    padding: 65px 7% 80px;
    border-radius: 0 0 20px 20px;
  }

  .portfolio-home .hero-inner,
  .portfolio-home .about-grid,
  .portfolio-home .skills-layout,
  .portfolio-home .projects-grid {
    grid-template-columns: 1fr;
  }

  .portfolio-home .hero-inner {
    text-align: center;
  }

  .portfolio-home .hero-description {
    margin-left: auto;
    margin-right: auto;
  }

  .portfolio-home .hero-buttons,
  .portfolio-home .hero-socials {
    justify-content: center;
  }

  .portfolio-home .profile-visual {
    margin-top: 25px;
  }

  .portfolio-home .profile-ring {
    width: 245px;
  }

  .portfolio-home .profile-caption {
    left: 4%;
  }

  .portfolio-home .quick-facts {
    grid-template-columns: repeat(2, 1fr);
    width: 90%;
    margin-top: -35px;
  }

  .portfolio-home .fact:nth-child(2) {
    border-right: none;
  }

  .portfolio-home .fact:nth-child(1),
  .portfolio-home .fact:nth-child(2) {
    border-bottom: 1px solid #e5ece6;
  }

  .portfolio-home .section-wrap {
    padding: 60px 6%;
  }

  .portfolio-home .expertise-grid {
    grid-template-columns: 1fr;
  }

  .portfolio-home .about-cards {
    grid-template-columns: 1fr 1fr;
  }

  .portfolio-home .training-panel {
    grid-template-columns: 1fr;
    padding: 30px 24px;
  }

  .portfolio-home .training-badge {
    justify-self: start;
  }
}

@media (prefers-reduced-motion: reduce) {
  .portfolio-home *,
  .portfolio-home *:before,
  .portfolio-home *:after {
    animation: none !important;
    transition: none !important;
    scroll-behavior: auto !important;
  }
}
</style>

<div class="portfolio-home">

  <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-inner">

      <div class="hero-copy">
        <div class="hero-label">WELCOME TO MY PROFESSIONAL PORTFOLIO</div>

        <h1>JANUARIES <em>MULI</em></h1>

        <h2>ICT Technician | Web Developer | Systems Developer | Cybersecurity Enthusiast</h2>

        <p class="hero-description">
          I am an Information and Communication Technology professional passionate about building reliable digital solutions, developing useful systems, strengthening IT infrastructure and exploring cybersecurity. I combine practical technical experience with creativity to solve real-world technology challenges.
        </p>

        <div class="hero-buttons">
          <a class="btn btn-gold" href="/resume/">Explore My Resume →</a>
          <a class="btn btn-outline" href="/projects/">View My Projects</a>
        </div>

        <div class="hero-socials">
          <a href="https://github.com/januariesmuli" target="_blank" rel="noopener">GitHub ↗</a>
          <a href="mailto:januariesmuli87@gmail.com">Email Me ↗</a>
          <a href="/contact/">Contact ↗</a>
        </div>
      </div>

      <div class="profile-visual">
        <div class="profile-ring">
          <img src="/assets/images/januaries.jpeg" alt="Portrait of Januaries Muli">
        </div>
        <div class="profile-caption">
          JANUARIES MULI
          <small>ICT Professional | Kenya</small>
        </div>
      </div>

    </div>
  </section>

  <!-- QUICK FACTS -->
  <div class="quick-facts">
    <div class="fact">
      <strong>ICT</strong>
      <span>Professional Experience</span>
    </div>
    <div class="fact">
      <strong>5+</strong>
      <span>Featured Projects & Initiatives</span>
    </div>
    <div class="fact">
      <strong>Web</strong>
      <span>Development & Systems</span>
    </div>
    <div class="fact">
      <strong>Cyber</strong>
      <span>Security Development</span>
    </div>
  </div>

  <!-- ABOUT ME -->
  <section class="section-wrap">
    <div class="section-heading">
      <span>Who I Am</span>
      <h2>About Me</h2>
      <p>Technology, innovation and practical problem-solving are at the centre of my professional journey.</p>
    </div>

    <div class="about-grid">
      <div class="about-copy">
        <h3>Turning Technology Into Practical Solutions</h3>

        <p>
          I am an ICT professional currently serving as a Diocesan ICT Technician at the Catholic Diocese of Maralal. My work involves supporting ICT infrastructure, maintaining computer systems, managing networks, developing websites and supporting digital transformation initiatives.
        </p>

        <p>
          I have practical experience in web development, database-driven applications, technical support, CCTV systems, biometric solutions, server maintenance and IT infrastructure. I enjoy identifying challenges and creating solutions that improve efficiency, reliability and service delivery.
        </p>

        <p>
          I am also developing my cybersecurity expertise through practical learning and professional training, with an interest in security analysis, vulnerability assessment and responsible security testing.
        </p>

        <div class="about-highlight">
          My professional goal is to use technology, innovation and cybersecurity knowledge to build secure, accessible and effective digital solutions.
        </div>
      </div>

      <div class="about-cards">
        <div class="about-card">
          <div class="symbol">💻</div>
          <h4>Development</h4>
          <p>Building websites, web applications and database-driven systems.</p>
        </div>

        <div class="about-card">
          <div class="symbol">🔐</div>
          <h4>Cybersecurity</h4>
          <p>Learning security analysis, vulnerability assessment and secure practices.</p>
        </div>

        <div class="about-card">
          <div class="symbol">🌐</div>
          <h4>Networking</h4>
          <p>Supporting network infrastructure, connectivity and ICT systems.</p>
        </div>

        <div class="about-card">
          <div class="symbol">🛠️</div>
          <h4>ICT Support</h4>
          <p>Maintaining hardware, software, servers and end-user environments.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- AREAS OF EXPERTISE -->
  <section class="section-wrap expertise-section">
    <div class="section-heading">
      <span>What I Do</span>
      <h2>Areas of Expertise</h2>
      <p>A combination of technical support, software development and infrastructure management.</p>
    </div>

    <div class="expertise-grid">
      <div class="expertise-card">
        <div class="symbol">⌨️</div>
        <h3>Web Development</h3>
        <p>Designing and developing responsive websites and web applications using HTML, CSS, JavaScript, PHP and MySQL.</p>
      </div>

      <div class="expertise-card">
        <div class="symbol">⚙️</div>
        <h3>Systems Development</h3>
        <p>Developing database-driven systems, managing records, implementing CRUD operations and improving workflows.</p>
      </div>

      <div class="expertise-card">
        <div class="symbol">🛡️</div>
        <h3>Cybersecurity</h3>
        <p>Building practical skills in security analysis, Linux, vulnerability assessment and authorized web application testing.</p>
      </div>

      <div class="expertise-card">
        <div class="symbol">🖧</div>
        <h3>Networking & Infrastructure</h3>
        <p>Supporting LAN connectivity, network troubleshooting, internet services and ICT infrastructure.</p>
      </div>

      <div class="expertise-card">
        <div class="symbol">📹</div>
        <h3>Security Systems</h3>
        <p>Installation and support of CCTV, biometric attendance and intercom systems.</p>
      </div>

      <div class="expertise-card">
        <div class="symbol">🔧</div>
        <h3>Technical Support</h3>
        <p>Computer maintenance, operating system installation, troubleshooting, backups and user support.</p>
      </div>
    </div>
  </section>

  <!-- TECHNICAL SKILLS -->
  <section class="section-wrap">
    <div class="section-heading">
      <span>My Technical Toolkit</span>
      <h2>Technical Skills</h2>
      <p>Technologies and tools I use, support or continue to develop through practical work.</p>
    </div>

    <div class="skills-layout">
      <div class="skill-group">
        <h3>Development & Databases</h3>
        <div class="skill-tags">
          <span>HTML5</span>
          <span>CSS3</span>
          <span>JavaScript</span>
          <span>PHP</span>
          <span>MySQL</span>
          <span>Bootstrap</span>
          <span>WordPress</span>
          <span>Git & GitHub</span>
          <span>XAMPP</span>
          <span>Database Design</span>
        </div>
      </div>

      <div class="skill-group">
        <h3>Cybersecurity & Systems</h3>
        <div class="skill-tags">
          <span>Linux</span>
          <span>Kali Linux</span>
          <span>SQL Injection Testing</span>
          <span>Vulnerability Assessment</span>
          <span>Web Security</span>
          <span>Networking</span>
          <span>Windows Administration</span>
          <span>Server Maintenance</span>
          <span>Backup & Recovery</span>
          <span>IT Support</span>
        </div>
      </div>
    </div>
  </section>

  <!-- FEATURED PROJECTS -->
  <section class="section-wrap projects-section">
    <div class="section-heading">
      <span>Selected Work</span>
      <h2>Featured Projects</h2>
      <p>Practical projects and technology initiatives demonstrating my experience and continuing development.</p>
    </div>

    <div class="projects-grid">

      <article class="project-card">
        <div class="project-top">
          <span>Website Development</span>
          <h3>Catholic Diocese of Maralal Website</h3>
        </div>
        <div class="project-body">
          <p>Development and maintenance of the diocesan website, providing a central online platform for diocesan news, events, institutions and information.</p>
          <details>
            <summary>Explore project details</summary>
            <p>Includes website content management, institutional information, news updates, online visibility and integration of diocesan communication resources.</p>
          </details>
          <a class="project-link" href="https://maralalcatholicdiocese.org/" target="_blank" rel="noopener">Visit Live Website ↗</a>
        </div>
      </article>

      <article class="project-card">
        <div class="project-top">
          <span>Media & Digital Platform</span>
          <h3>Radio Mchungaji Website</h3>
        </div>
        <div class="project-body">
          <p>A digital platform for Radio Mchungaji, supporting online radio streaming, programme information and communication with listeners.</p>
          <details>
            <summary>Explore project details</summary>
            <p>The platform supports online access to the radio stream, programme presentation and digital outreach for the Catholic Diocese of Maralal.</p>
          </details>
          <a class="project-link" href="https://radiomchungaji.co.ke/" target="_blank" rel="noopener">Visit Live Website ↗</a>
        </div>
      </article>

      <article class="project-card">
        <div class="project-top">
          <span>Systems Development</span>
          <h3>CDM ERP – Contributions Management</h3>
        </div>
        <div class="project-body">
          <p>A PHP and MySQL-based system under development to support diocesan and parish contribution management and reporting.</p>
          <details>
            <summary>Explore project details</summary>
            <p>Planned and implemented features include contribution records, parish and diocesan tracking, allocation calculations, analytics, reporting, user roles and audit logs.</p>
          </details>
          <a class="project-link" href="/projects/">View Project Overview →</a>
        </div>
      </article>

      <article class="project-card">
        <div class="project-top">
          <span>Healthcare ICT Support</span>
          <h3>Wamba Hospital Management System</h3>
        </div>
        <div class="project-body">
          <p>Technical deployment and support of a hospital management system covering key healthcare service areas.</p>
          <details>
            <summary>Explore project details</summary>
            <p>Deployment support included inpatient and outpatient workflows, laboratory, pharmacy, medicine pricing, connectivity and user access support.</p>
          </details>
          <a class="project-link" href="/projects/">View Project Overview →</a>
        </div>
      </article>

      <article class="project-card">
        <div class="project-top">
          <span>Cybersecurity Learning</span>
          <h3>Cybersecurity Practical Labs</h3>
        </div>
        <div class="project-body">
          <p>Hands-on cybersecurity exercises focused on understanding web application security and Linux environments in authorized training labs.</p>
          <details>
            <summary>Explore project details</summary>
            <p>Practical topics include SQL injection, parameter discovery, web application testing and Linux command-line enumeration.</p>
          </details>
          <a class="project-link" href="/labs/">Explore Lab Challenges →</a>
        </div>
      </article>

    </div>

    <div style="text-align:center; margin-top:38px;">
      <a class="btn btn-gold" href="/projects/">Explore All Projects →</a>
    </div>
  </section>

  <!-- PROFESSIONAL DEVELOPMENT -->
  <section class="section-wrap">
    <div class="section-heading">
      <span>Continuous Learning</span>
      <h2>Professional Development</h2>
      <p>Expanding my knowledge through structured training and practical experience.</p>
    </div>

    <div class="training-panel">
      <div>
        <div class="eyebrow">Cybersecurity Professional Training</div>
        <h3>Cyber Shujaa Programme – Security Analyst Track</h3>
        <p>
          Currently undertaking the Cyber Shujaa Security Analyst Track in collaboration with USIU-Africa. The programme supports my development in cybersecurity through structured learning, practical exercises and security analysis training.
        </p>
        <p style="margin-top:13px;">
          <strong>Institution:</strong> United States International University-Africa (USIU-Africa)<br>
          <strong>Training period:</strong> August – December 2026
        </p>
        <a class="btn btn-gold" href="/resume/" style="margin-top:22px;">View Education & Training →</a>
      </div>
      <div class="training-badge">
        CYBER SHUJAA<br>
        SECURITY ANALYST<br>
        TRACK · 2026
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="section-wrap contact-section">
    <div class="contact-panel">
      <h2>Let's Connect & Build Something Great</h2>
      <p>
        I am open to professional opportunities, technology collaborations, ICT projects and knowledge-sharing opportunities. Feel free to reach out.
      </p>

      <div class="contact-details">
        <a href="mailto:januariesmuli87@gmail.com">✉ Email Me</a>
        <a href="tel:+254793994571">☎ +254 793 994 571</a>
        <a href="https://github.com/januariesmuli" target="_blank" rel="noopener">GitHub ↗</a>
        <a href="/contact/">Contact Page →</a>
      </div>

      <a class="btn btn-gold" href="/contact/">Get In Touch →</a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="portfolio-footer">
    <strong>JANUARIES MULI</strong><br>
    ICT Technician | Web Developer | Systems Developer | Cybersecurity Enthusiast<br>
    <span style="opacity:.7;">© 2026 Januaries Muli. All Rights Reserved.</span>
  </footer>

</div>
