---
layout: single
title: "My Projects"
permalink: /projects/
author_profile: true
classes: wide
---

<style>
.projects-page {
  --green: #024115;
  --dark: #062b18;
  --gold: #c69b35;
  --light: #f0f6f1;
  --text: #26352b;
  color: var(--text);
  line-height: 1.75;
}

.projects-page * {
  box-sizing: border-box;
}

.projects-page .hero {
  background: linear-gradient(135deg, #062b18, #07552b);
  color: white;
  padding: 48px 28px;
  border-radius: 17px;
  border-bottom: 5px solid var(--gold);
  text-align: center;
  margin: 20px 0 35px;
}

.projects-page .hero .eyebrow {
  color: #e3c16b;
  font-weight: 800;
  letter-spacing: 3px;
  text-transform: uppercase;
  font-size: .8rem;
}

.projects-page .hero h1 {
  color: white;
  font-size: clamp(2rem, 5vw, 3.2rem);
  margin: 12px 0;
  border: none;
}

.projects-page .hero p {
  color: #e8f2e9;
  max-width: 720px;
  margin: auto;
}

.projects-page .section-title {
  color: var(--green);
  border-bottom: 2px solid var(--gold);
  padding-bottom: 10px;
  margin: 42px 0 20px;
}

.projects-page .project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(270px, 1fr));
  gap: 22px;
  margin: 25px 0;
}

.projects-page .project-card {
  background: #fff;
  border: 1px solid #dce8df;
  border-top: 5px solid var(--green);
  border-radius: 13px;
  padding: 23px;
  box-shadow: 0 5px 18px rgba(0,0,0,.05);
  transition: transform .25s ease, box-shadow .25s ease;
}

.projects-page .project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 25px rgba(0,0,0,.10);
}

.projects-page .project-number {
  color: #a47b20;
  font-weight: 800;
  font-size: .78rem;
  letter-spacing: 1.5px;
  text-transform: uppercase;
}

.projects-page .project-card h3 {
  color: var(--green);
  border: none;
  margin: 10px 0;
  font-size: 1.2rem;
}

.projects-page .project-icon {
  font-size: 2rem;
  margin-bottom: 8px;
}

.projects-page .project-status {
  display: inline-block;
  background: var(--light);
  color: var(--green);
  border: 1px solid #c9dfcc;
  border-radius: 20px;
  padding: 4px 11px;
  font-size: .75rem;
  font-weight: 800;
  margin: 8px 0 13px;
}

.projects-page .project-card ul {
  padding-left: 20px;
}

.projects-page .project-card li {
  margin-bottom: 5px;
}

.projects-page .tech-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin: 17px 0;
}

.projects-page .tech-stack span {
  background: #e8f2e9;
  color: #06421b;
  border: 1px solid #c9dfcc;
  padding: 5px 10px;
  border-radius: 5px;
  font-size: .78rem;
  font-weight: 600;
}

.projects-page .project-link {
  display: inline-block;
  background: var(--green);
  color: white !important;
  padding: 10px 17px;
  border-radius: 7px;
  font-weight: 700;
  text-decoration: none;
  margin-top: 10px;
}

.projects-page .project-link:hover {
  background: var(--gold);
  color: #102316 !important;
  text-decoration: none;
}

.projects-page .info-box {
  background: var(--light);
  border-left: 5px solid var(--gold);
  padding: 23px;
  border-radius: 10px;
  margin: 25px 0;
}

.projects-page .info-box h3 {
  color: var(--green);
  margin-top: 0;
}

.projects-page .cta {
  background: linear-gradient(135deg, #062b18, #07552b);
  color: white;
  text-align: center;
  padding: 40px 25px;
  border-radius: 15px;
  margin-top: 45px;
}

.projects-page .cta h2 {
  color: white;
  border: none;
  margin-top: 0;
}

.projects-page .cta p {
  color: #e8f2e9;
}

.projects-page .cta a {
  display: inline-block;
  background: var(--gold);
  color: #102316 !important;
  padding: 12px 23px;
  border-radius: 7px;
  font-weight: 800;
  text-decoration: none;
  margin-top: 12px;
}

@media(max-width:600px) {
  .projects-page .hero {
    padding: 32px 18px;
  }

  .projects-page .project-card {
    padding: 19px;
  }
}
</style>

<div class="projects-page">

  <section class="hero">
    <p class="eyebrow">Innovation • Development • Technology</p>

    <h1>My Projects Portfolio</h1>

    <p>
      Welcome to my project portfolio. Explore selected ICT projects,
      web applications, digital platforms, enterprise systems and
      cybersecurity practical work developed or supported through
      my professional experience and technical training.
    </p>
  </section>

  <h2 class="section-title">Featured Projects</h2>

  <div class="project-grid">

    <article class="project-card">
      <div class="project-icon">🌐</div>

      <p class="project-number">PROJECT 01 | WEB DEVELOPMENT</p>

      <h3>Catholic Diocese of Maralal Website</h3>

      <span class="project-status">Live Project</span>

      <p>
        Development and maintenance of the official website for
        the Catholic Diocese of Maralal, providing a central digital
        platform for communication, public information and institutional visibility.
      </p>

      <strong>Key Features</strong>

      <ul>
        <li>Institutional news and announcements.</li>
        <li>Events and diocesan information.</li>
        <li>Website content and page management.</li>
        <li>Domain and SSL management.</li>
        <li>Digital communication and online visibility.</li>
      </ul>

      <div class="tech-stack">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>WordPress</span>
      </div>

      <a class="project-link"
         href="https://maralalcatholicdiocese.org/"
         target="_blank" rel="noopener noreferrer">
        Visit Live Website →
      </a>
    </article>

    <article class="project-card">
      <div class="project-icon">📻</div>

      <p class="project-number">PROJECT 02 | DIGITAL MEDIA</p>

      <h3>Radio Mchungaji Website</h3>

      <span class="project-status">Live Project</span>

      <p>
        Development and maintenance of the Radio Mchungaji digital
        platform, supporting Catholic evangelization, online radio
        broadcasting and audience engagement.
      </p>

      <strong>Key Features</strong>

      <ul>
        <li>Radio website design and development.</li>
        <li>Online radio streaming integration.</li>
        <li>Programme and presenter information.</li>
        <li>Digital media communication.</li>
        <li>Content management and website maintenance.</li>
      </ul>

      <div class="tech-stack">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>WordPress</span>
      </div>

      <a class="project-link"
         href="https://radiomchungaji.co.ke/"
         target="_blank" rel="noopener noreferrer">
        Visit Live Website →
      </a>
    </article>

    <article class="project-card">
      <div class="project-icon">📊</div>

      <p class="project-number">PROJECT 03 | ENTERPRISE SYSTEMS</p>

      <h3>CDM ERP – Contributions Management System</h3>

      <span class="project-status">Under Development</span>

      <p>
        Development of a PHP and MySQL-based enterprise system
        designed to support contribution recording, financial
        tracking and reporting across diocesan offices and parishes.
      </p>

      <strong>Key Features</strong>

      <ul>
        <li>Contribution and collection recording.</li>
        <li>Parish and diocesan contribution tracking.</li>
        <li>Automated contribution allocation calculations.</li>
        <li>Performance analytics and reporting.</li>
        <li>User roles and access control.</li>
        <li>Audit logs and system security.</li>
      </ul>

      <div class="tech-stack">
        <span>PHP</span>
        <span>MySQL</span>
        <span>Bootstrap</span>
        <span>JavaScript</span>
        <span>AJAX</span>
      </div>
    </article>

    <article class="project-card">
      <div class="project-icon">🏥</div>

      <p class="project-number">PROJECT 04 | HEALTHCARE TECHNOLOGY</p>

      <h3>Wamba Hospital Management System</h3>

      <span class="project-status">Deployment Support</span>

      <p>
        Supported the deployment and configuration of a hospital
        management system at Wamba Hospital to improve digital
        management of healthcare services.
      </p>

      <strong>Key Features</strong>

      <ul>
        <li>Inpatient and outpatient modules.</li>
        <li>Laboratory and pharmacy configuration.</li>
        <li>Medicine and service pricing.</li>
        <li>User access and system administration.</li>
        <li>Internet connectivity and technical support.</li>
      </ul>

      <div class="tech-stack">
        <span>System Deployment</span>
        <span>Database Support</span>
        <span>Networking</span>
        <span>ICT Support</span>
      </div>
    </article>

    <article class="project-card">
      <div class="project-icon">🔐</div>

      <p class="project-number">PROJECT 05 | CYBERSECURITY</p>

      <h3>Cybersecurity Practical Labs</h3>

      <span class="project-status">Training and Practical Learning</span>

      <p>
        Hands-on cybersecurity exercises conducted in authorized
        training environments to develop practical knowledge of
        web application security, vulnerability assessment and
        Linux administration.
      </p>

      <strong>Areas of Practice</strong>

      <ul>
        <li>SQL injection testing in controlled labs.</li>
        <li>Web parameter discovery and fuzzing.</li>
        <li>Linux command-line enumeration.</li>
        <li>Web application vulnerability assessment.</li>
        <li>Security testing and technical documentation.</li>
      </ul>

      <div class="tech-stack">
        <span>Kali Linux</span>
        <span>SQLMap</span>
        <span>Linux</span>
        <span>Web Security</span>
        <span>Networking</span>
      </div>

      <a class="project-link" href="/labs/">
        Explore Lab Challenges →
      </a>
    </article>

  </div>

  <h2 class="section-title">Professional Development</h2>

  <div class="info-box">
    <h3>Cyber Shujaa Programme – Security Analyst Track</h3>

    <p>
      <strong>United States International University-Africa (USIU-Africa)</strong>
      <br>
      <strong>August – December 2026</strong>
    </p>

    <p>
      Participating in cybersecurity professional training through
      the Cyber Shujaa Programme, focusing on security analysis,
      practical cybersecurity skills, information security and
      risk management.
    </p>

    <p>
      The programme supports my continued development in
      cybersecurity and professional security analysis.
    </p>
  </div>

  <h2 class="section-title">Technologies and Tools</h2>

  <p>
    The following technologies and tools form part of my development,
    administration and cybersecurity learning environment.
  </p>

  <div class="tech-stack">
    <span>HTML5</span>
    <span>CSS3</span>
    <span>JavaScript</span>
    <span>PHP</span>
    <span>MySQL</span>
    <span>Bootstrap</span>
    <span>WordPress</span>
    <span>Git</span>
    <span>GitHub</span>
    <span>XAMPP</span>
    <span>Kali Linux</span>
    <span>Linux</span>
    <span>SQLMap</span>
    <span>Windows</span>
    <span>Networking</span>
  </div>

  <section class="cta">
    <h2>Interested in Working Together?</h2>

    <p>
      I welcome opportunities to collaborate on ICT projects,
      web development, systems development, cybersecurity
      initiatives and digital transformation.
    </p>

    <a href="/contact/">Get in Touch →</a>
  </section>

</div>
