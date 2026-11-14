---
layout: single
title: "Cybersecurity Lab Challenges"
permalink: /labs/
author_profile: true
classes: wide
---

<style>
.lab-page {
  --green: #024115;
  --dark: #062b18;
  --gold: #c69b35;
  --light: #f0f6f1;
  --text: #26352b;
  color: var(--text);
  line-height: 1.75;
}

.lab-page .hero {
  background: linear-gradient(135deg, #062b18, #07552b);
  color: white;
  padding: 48px 28px;
  border-radius: 17px;
  border-bottom: 5px solid var(--gold);
  text-align: center;
  margin: 20px 0 35px;
}

.lab-page .hero .eyebrow {
  color: #e3c16b;
  font-weight: 800;
  letter-spacing: 2px;
  text-transform: uppercase;
  font-size: .8rem;
}

.lab-page .hero h1 {
  color: white;
  font-size: clamp(2rem, 5vw, 3.2rem);
  margin: 12px 0;
}

.lab-page .hero p {
  color: #e8f2e9;
  max-width: 750px;
  margin: auto;
}

.lab-page .section-title {
  color: var(--green);
  border-bottom: 2px solid var(--gold);
  padding-bottom: 10px;
  margin: 42px 0 22px;
}

.lab-page .intro {
  background: var(--light);
  border-left: 5px solid var(--gold);
  padding: 22px;
  border-radius: 10px;
  margin: 25px 0;
}

.lab-page .lab-card {
  background: white;
  border: 1px solid #dce8df;
  border-radius: 14px;
  border-top: 5px solid var(--green);
  padding: 27px;
  margin: 28px 0;
  box-shadow: 0 5px 18px rgba(0,0,0,.05);
}

.lab-page .lab-number {
  color: #9b741e;
  font-size: .78rem;
  font-weight: 800;
  letter-spacing: 1.5px;
  text-transform: uppercase;
}

.lab-page .lab-card h2 {
  color: var(--green);
  border: 0;
  margin: 8px 0 15px;
}

.lab-page .lab-card h3 {
  color: var(--green);
  border: 0;
  font-size: 1.05rem;
  margin-top: 24px;
}

.lab-page .status {
  display: inline-block;
  background: var(--light);
  color: var(--green);
  border: 1px solid #c9dfcc;
  border-radius: 20px;
  padding: 4px 12px;
  font-size: .76rem;
  font-weight: 800;
  margin: 5px 0 15px;
}

.lab-page .tools {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 14px 0;
}

.lab-page .tools span {
  background: #e8f2e9;
  color: #06421b;
  border: 1px solid #c9dfcc;
  padding: 6px 11px;
  border-radius: 6px;
  font-size: .82rem;
  font-weight: 600;
}

.lab-page .lesson {
  background: #fffaf0;
  border-left: 4px solid var(--gold);
  padding: 17px 20px;
  border-radius: 8px;
  margin-top: 20px;
}

.lab-page .screenshot {
  background: #f4f6f4;
  border: 2px dashed #a7b9aa;
  padding: 25px 15px;
  border-radius: 10px;
  text-align: center;
  margin: 18px 0;
  color: #59695e;
}

.lab-page .screenshot strong {
  color: var(--green);
  display: block;
  margin-bottom: 6px;
}

.lab-page .method {
  background: #f5f7f5;
  border-radius: 8px;
  padding: 15px 18px;
  margin: 15px 0;
}

.lab-page .method li {
  margin-bottom: 7px;
}

.lab-page .disclaimer {
  background: var(--light);
  border-left: 5px solid var(--green);
  border-radius: 9px;
  padding: 20px;
  margin: 30px 0;
}

.lab-page .cta {
  background: linear-gradient(135deg, #062b18, #07552b);
  color: white;
  text-align: center;
  padding: 38px 24px;
  border-radius: 15px;
  margin-top: 40px;
}

.lab-page .cta h2 {
  color: white;
  border: 0;
  margin-top: 0;
}

.lab-page .cta p {
  color: #e8f2e9;
}

.lab-page .cta a {
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
  .lab-page .hero {
    padding: 32px 18px;
  }

  .lab-page .lab-card {
    padding: 19px;
  }
}
</style>

<div class="lab-page">

<div class="hero">

<p class="eyebrow">Cybersecurity • Ethical Hacking • Practical Learning</p>

<h1>Cybersecurity Lab Challenges</h1>

<p>
Welcome to my cybersecurity laboratory portfolio. This section documents practical security exercises, Capture The Flag (CTF) activities and technical challenges undertaken to strengthen my knowledge of ethical hacking, vulnerability assessment, web application security and Linux administration.
</p>

</div>

<h2 class="section-title">About My Lab Practice</h2>

<div class="intro">

I use controlled cybersecurity training environments to develop practical skills in identifying vulnerabilities, analysing application behaviour, investigating security weaknesses and understanding how systems can be protected against attacks.

My practical learning focuses on:

- Web application security testing.
- SQL injection identification and analysis.
- Database security and controlled data extraction.
- Linux system enumeration.
- Web parameter discovery and fuzzing.
- Vulnerability assessment and documentation.
- Security analysis and problem-solving.

</div>

<h2 class="section-title">Featured Lab Challenges</h2>

<!-- CHALLENGE 1 -->

<div class="lab-card">

<p class="lab-number">CHALLENGE 01 | WEB APPLICATION SECURITY</p>

<h2>SQL Injection and Database Extraction</h2>

<span class="status">Completed Training Lab</span>

<h3>Problem Statement</h3>

The challenge involved investigating a web application that accepted user input through URL parameters. The objective was to identify whether the application was vulnerable to SQL injection and demonstrate the security implications of insufficient input validation in an authorized training environment.

<h3>Approach and Methodology</h3>

<div class="method">

1. Examined the application's URL parameters and request behaviour.
2. Identified a parameter that appeared to interact with a database query.
3. Tested the application's responses to determine whether user input was handled securely.
4. Investigated the database query structure and tested the number of returned columns in the controlled lab.
5. Used SQL injection testing techniques to demonstrate the vulnerability.
6. Investigated the permitted file-reading functionality within the lab environment.
7. Documented the findings and security implications.

</div>

<h3>Tools Used</h3>

<div class="tools">
<span>Kali Linux</span>
<span>SQLMap</span>
<span>cURL</span>
<span>Web Browser</span>
<span>Linux Terminal</span>
</div>

<h3>Evidence and Screenshots</h3>


<div class="screenshot">
  <strong>Screenshot 01 – SQL Injection Testing</strong>

  <img
    src="/assets/images/labs/sql-injection/SQL Injection.png"
    alt="SQL injection testing and parameter investigation in an authorized cybersecurity lab"
    style="width:100%; height:auto; display:block; margin-top:15px; border-radius:12px;"
  >

  <p>
    Evidence showing the authorized SQL injection testing process
    and parameter investigation.
  </p>
</div>

<div class="screenshot">
  <strong>Screenshot 01 – SQL Injection Testing</strong>

  <img
    src="/assets/images/labs/sql-injection/SQL Injection 2.png"
    alt="SQL injection testing and parameter investigation in an authorized cybersecurity lab"
    style="width:100%; height:auto; display:block; margin-top:15px; border-radius:12px;"
  >

  <p>
    Evidence showing the authorized SQL injection testing process
    and parameter investigation.
  </p>
</div>


<h3>Key Lessons Learned</h3>

- Learned how insecure database queries can expose applications to SQL injection.
- Improved understanding of URL parameters and database query behaviour.
- Gained practical experience using SQLMap and cURL.
- Learned the importance of input validation and parameterized SQL queries.
- Improved technical documentation and vulnerability analysis skills.

</div>

<!-- CHALLENGE 2 -->

<div class="lab-card">

<p class="lab-number">CHALLENGE 02 | WEB RECONNAISSANCE</p>

<h2>Web Application Parameter Discovery and Fuzzing</h2>

<span class="status">Practical Training</span>

<h3>Problem Statement</h3>

The challenge involved examining a web application to understand how it handled different URL parameters and user-supplied input. The objective was to identify application behaviour, discover potentially interesting input points and understand how poor input handling could introduce security vulnerabilities.

<h3>Approach and Methodology</h3>

<div class="method">

1. Inspected the application's accessible pages and request structure.
2. Identified URL parameters and input fields.
3. Observed how the application responded to different test inputs.
4. Used controlled parameter testing and fuzzing techniques.
5. Compared application responses to identify unusual behaviour.
6. Documented potentially vulnerable input points for further investigation.

</div>

<h3>Tools Used</h3>

<div class="tools">
<span>Kali Linux</span>
<span>cURL</span>
<span>Web Browser</span>
<span>Linux Terminal</span>
<span>Fuzzing Tools</span>
</div>

<h3>Evidence and Screenshots</h3>

<div class="screenshot">
<strong>Screenshot 01 – Parameter Discovery</strong>
Add a screenshot showing the application request and identified parameters.
</div>

<div class="screenshot">
<strong>Screenshot 02 – Testing Results</strong>
Add a screenshot showing the comparison of application responses during controlled testing.
</div>

<h3>Key Lessons Learned</h3>

- Understood the importance of web application reconnaissance.
- Improved knowledge of HTTP requests and URL parameters.
- Learned how to investigate application responses systematically.
- Developed a better understanding of input validation and attack surfaces.
- Improved troubleshooting and analytical skills.

</div>

<!-- CHALLENGE 3 -->

<div class="lab-card">

<p class="lab-number">CHALLENGE 03 | LINUX SYSTEM ENUMERATION</p>

<h2>Linux Command-Line Enumeration</h2>

<span class="status">Completed Practical Exercise</span>

<h3>Problem Statement</h3>

The exercise involved interacting with a Linux-based environment to identify the current user, understand the working directory and inspect accessible files and directories.

The objective was to develop familiarity with Linux command-line operations and basic system enumeration techniques.

<h3>Approach and Methodology</h3>

<div class="method">

1. Established access to the authorized lab environment.
2. Executed commands to identify the current system user.
3. Checked the current working directory.
4. Inspected directory contents and file permissions.
5. Investigated accessible files and system information.
6. Recorded findings for further security analysis.

</div>

<h3>Tools and Commands Used</h3>

<div class="tools">
<span>Kali Linux</span>
<span>Linux Terminal</span>
<span>whoami</span>
<span>pwd</span>
<span>ls -la</span>
<span>Command Line</span>
</div>

<h3>Evidence and Screenshots</h3>

<div class="screenshot">
<strong>Screenshot 01 – User Identification</strong>
Add a screenshot showing the whoami command and its result.
</div>

<div class="screenshot">
<strong>Screenshot 02 – Directory Enumeration</strong>
Add a screenshot showing pwd and ls -la results from the authorized lab.
</div>

<h3>Key Lessons Learned</h3>

- Improved confidence using Linux command-line tools.
- Learned how to identify the current user and working directory.
- Improved understanding of Linux directory structures.
- Gained experience inspecting files and permissions.
- Developed foundational system enumeration skills.

</div>

<h2 class="section-title">Skills Developed Through Lab Challenges</h2>

<div class="tools">
<span>Ethical Hacking</span>
<span>SQL Injection Analysis</span>
<span>Web Security</span>
<span>Linux Enumeration</span>
<span>Reconnaissance</span>
<span>Parameter Testing</span>
<span>Vulnerability Assessment</span>
<span>SQLMap</span>
<span>cURL</span>
<span>Security Documentation</span>
<span>Problem Solving</span>
<span>Technical Analysis</span>
</div>

<h2 class="section-title">Training and Continuous Learning</h2>

<div class="intro">

<strong>Cyber Shujaa Programme – Security Analyst Track</strong>

**United States International University-Africa (USIU-Africa)**

**August – December 2026**

I am developing my cybersecurity knowledge through the Cyber Shujaa Security Analyst training programme, combining structured learning with practical exercises and hands-on security challenges.

My goal is to strengthen my skills in security analysis, vulnerability assessment, threat identification and information security.

</div>

<div class="disclaimer">

<strong>Ethical and Responsible Security Practice</strong>

All practical security exercises documented on this page are intended for authorized training environments, educational laboratories and systems where permission has been granted. Security testing must always be conducted responsibly and within an approved scope.

</div>

<div class="cta">

<h2>Interested in My Cybersecurity Journey?</h2>

<p>
I am continuously learning, practising and documenting cybersecurity techniques as I develop my skills in ethical hacking and security analysis.
</p>

<a href="/contact/">Connect With Me →</a>

</div>

</div>
