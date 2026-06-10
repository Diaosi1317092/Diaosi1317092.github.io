---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-page {
  font-size: 0.98rem;
  line-height: 1.55;
}

.cv-section {
  margin-top: 2.0rem;
  margin-bottom: 1.0rem;
  border-bottom: 1px solid #d8d8d8;
  padding-bottom: 0.25rem;
  font-size: 1.45rem;
  font-weight: 700;
  letter-spacing: 0.02em;
}

.cv-card {
  margin: 1.05rem 0 1.35rem 0;
  padding: 0.95rem 1.1rem;
  border-left: 4px solid #2f6f9f;
  background: #fafafa;
  border-radius: 6px;
}

.cv-title {
  font-size: 1.08rem;
  font-weight: 700;
  margin-bottom: 0.18rem;
}

.cv-meta {
  color: #555;
  font-size: 0.95rem;
  margin-bottom: 0.45rem;
}

.cv-note {
  margin: 0.25rem 0;
}

.cv-card ul {
  margin-top: 0.35rem;
  margin-bottom: 0;
}

.cv-card li {
  margin-bottom: 0.22rem;
}

.cv-badge-gold {
  color: #ff9800;
  font-weight: 700;
}

.cv-badge-silver {
  color: #9e9e9e;
  font-weight: 700;
}

.cv-badge-orange {
  color: orange;
  font-weight: 700;
}

.cv-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 0.8rem;
}

.cv-compact-list {
  margin-top: 0.4rem;
}

.cv-compact-list li {
  margin-bottom: 0.25rem;
}

.cv-small {
  color: #666;
  font-size: 0.94rem;
}

.cv-linkline {
  margin-top: 0.25rem;
}
</style>

<div class="cv-page">

<div class="cv-section">Education</div>

<div class="cv-card">
  <div class="cv-title">B.S. in Computer Science and Technology (Turing Class)</div>
  <div class="cv-meta">Southern University of Science and Technology, 2023 – Present</div>
</div>

<div class="cv-section">Research Experience</div>

<div class="cv-card">
  <div class="cv-title">Research Assistant <span class="cv-small">(Expected)</span></div>
  <div class="cv-meta">Fall 2026 · LIX – Laboratoire d’informatique de l’École polytechnique, École Polytechnique</div>
  <div class="cv-note"><strong>Supervisor:</strong> Professor Benjamin Doerr</div>
  <ul>
    <li>Expected to work on mathematical runtime analysis of randomized search heuristics and hyper-heuristics, with a focus on rigorous analysis of randomized optimization processes.</li>
    <li>Planned research directions include hyper-heuristics on multimodal optimization problems, adaptive operator selection, phase transitions in heuristic performance, and advanced runtime-analysis techniques.</li>
  </ul>
</div>

<div class="cv-card">
  <div class="cv-title">Research Assistant</div>
  <div class="cv-meta">Spring 2025 · Theory of AI Lab, Southern University of Science and Technology</div>
  <div class="cv-note"><strong>Supervisor:</strong> Professor Pietro S. Oliveto</div>
  <ul>
    <li>Conducted theoretical research on randomized algorithms, reinforcement learning hyper-heuristics, and runtime analysis of learning-based selection mechanisms.</li>
    <li>Studied how parameter settings affect the ability of reinforcement learning hyper-heuristics to identify useful low-level heuristics during the optimization process.</li>
    <li>Developed and verified formal runtime arguments using tools from drift analysis, probabilistic inequalities, and randomized search heuristic theory.</li>
  </ul>
</div>

<div class="cv-section">Competitive Programming</div>

<div class="cv-card">
  <div class="cv-title">Codeforces</div>
  <p>
    I am an <span class="cv-badge-orange">International Master</span> on Codeforces
    (<strong>Max Rating 2314</strong>).
  </p>

  <div class="cv-title" style="margin-top: 0.8rem;">Awards</div>
  <ul class="cv-compact-list">
    <li><strong>49th International Collegiate Programming Contest Hangzhou Regional Contest:</strong> <span class="cv-badge-gold">Gold Medal</span></li>
    <li><strong>10th China Collegiate Programming Contest Zhengzhou Regional Contest:</strong> <span class="cv-badge-gold">Gold Medal</span></li>
    <li><strong>49th International Collegiate Programming Contest Shenyang Regional Contest:</strong> <span class="cv-badge-silver">Silver Medal</span></li>
    <li><strong>49th International Collegiate Programming Contest East-Continent Finals:</strong> <span class="cv-badge-silver">Silver Medal</span></li>
  </ul>

  <div class="cv-title" style="margin-top: 0.8rem;">Problem Setting and Judging</div>
  <ul class="cv-compact-list">
    <li><strong>The 3rd Universal Cup Finals:</strong> Problem Selection Committee Member; Problem Setter</li>
  </ul>
</div>

<div class="cv-section">Courses</div>

<div class="cv-card">
  <div class="cv-title">Selected Coursework</div>
  <ul class="cv-compact-list">
    <li><strong>Average Mark:</strong> 89.25/100</li>
    <li><strong>CS217 Data Structures and Algorithm Analysis (Honors)</strong>, Fall 2024 — Final Grade: <strong>100/100</strong></li>
    <li><strong>CS216 Algorithm Design and Analysis (Honors)</strong>, Spring 2025 — Final Grade: <strong>99/100</strong></li>
  </ul>
</div>

<div class="cv-section">Teaching</div>

<div class="cv-card">
  <div class="cv-title">Teaching Assistant</div>
  <div class="cv-meta">CS217 Data Structures and Algorithm Analysis (Honors), Fall 2025</div>
</div>

<div class="cv-section">Projects</div>

<div class="cv-card">
  <div class="cv-title">Course Grading System</div>
  <div class="cv-meta">Spring 2025 · CS304 Software Engineering</div>
  <p>
    Developed a full-stack academic grading platform integrating code evaluation, handwritten assignment grading,
    attendance tracking, grading feedback, and dispute management. The system supports OCR-assisted processing of
    handwritten assignments and GPT-4o-based AI grading support, aiming to improve grading efficiency, feedback
    quality, and teacher-student communication in course management.
  </p>
  <ul class="cv-compact-list">
    <li><strong>Tech stack:</strong> Vue.js, Express.js, PostgreSQL, OpenCV.js, Google Cloud Vision, GPT-4o (API).</li>
    <li><strong>Repository:</strong> <a href="https://github.com/sustech-cs304/team-project-25spring-team22">Course Grading System</a></li>
    <li><strong>Final Grade:</strong> 100/100</li>
  </ul>
</div>

<div class="cv-card">
  <div class="cv-title">Five-stage Pipeline CPU</div>
  <div class="cv-meta">Spring 2025 · CS202 Computer Organization & Design</div>
  <p>
    Designed and implemented a RISC-V32 CPU, including both single-cycle and five-stage pipeline architectures,
    and deployed the design on the EGO1 FPGA board. The pipelined version supports hazard handling, forwarding,
    stalling, branch prediction, and UART-based debugging. I also developed Python front-end tools for serial
    communication, register visualization, instruction decoding, and software-assisted branch prediction optimization,
    achieving stable execution of the pipelined CPU at up to 75 MHz.
  </p>
  <ul class="cv-compact-list">
    <li><strong>Tech stack:</strong> Verilog, EGO1 FPGA, UART, Python.</li>
    <li><strong>Repository:</strong> <a href="https://github.com/Diaosi1317092/Computer-Organization-Project">Five-stage Pipeline CPU</a></li>
    <li><strong>Final Grade:</strong> 115/100</li>
  </ul>
</div>

<div class="cv-card">
  <div class="cv-title">Reversed-Reversi</div>
  <div class="cv-meta">Spring 2025 · CS311 Artificial Intelligence (Honors)</div>
  <p>
    Implemented an AI agent for Reversed Reversi under strict platform constraints on time, memory, legality,
    and online round-robin competitiveness. The agent combines efficient move generation, board evaluation,
    and search/heuristic strategies for adversarial decision making in a modified Reversi setting, with computation
    optimized using NumPy and Numba. The final submission achieved <strong>Top 5 Player</strong> on the course competition platform.
  </p>
  <ul class="cv-compact-list">
    <li><strong>Tech stack:</strong> Python, NumPy, Numba.</li>
    <li><strong>Repository:</strong> <a href="https://github.com/Diaosi1317092/Reversed-Reversi">Reversed-Reversi</a></li>
    <li><strong>Final Grade:</strong> 99/100</li>
  </ul>
</div>

<div class="cv-card">
  <div class="cv-title">Range Hood Program</div>
  <div class="cv-meta">Fall 2024 · CS211 Digital Logic (Honors)</div>
  <p>
    Designed and implemented a range hood control system on FPGA, supporting power control, time display,
    fan-speed switching, countdown modes, self-cleaning, manual cleaning, lighting, and smart reminders.
    The system was built with modular Verilog state-machine design and integrated external devices including
    a 4×4 membrane keyboard for input and an LCD1602 display for real-time status and countdown output.
  </p>
  <ul class="cv-compact-list">
    <li><strong>Tech stack:</strong> Verilog, EGO1 FPGA, 4×4 membrane keyboard, LCD1602.</li>
    <li><strong>Repository:</strong> <a href="https://github.com/Diaosi1317092/Digital-Logic-Project">Range Hood Program</a></li>
    <li><strong>Final Grade:</strong> 115/100</li>
  </ul>
</div>

<div class="cv-section">Skills</div>

<div class="cv-card">
  <div class="cv-title">Programming</div>
  <p>Modern C++, Python, Rust; Verilog for hardware development; JavaScript for front-end development.</p>

  <div class="cv-title" style="margin-top: 0.8rem;">Languages</div>
  <p>Native in Chinese; fluent in English.</p>
</div>

</div>
