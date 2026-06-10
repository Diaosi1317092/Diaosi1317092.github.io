---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<style>
  :root {
    --cv-card-bg: #ffffff;
    --cv-border: #e5e7eb;
    --cv-muted: #666;
    --cv-strong: #222;
    --cv-text: #333;
    --cv-accent: #2f6f9f;
    --cv-pill-bg: rgba(47, 111, 159, 0.10);
    --cv-pill-border: rgba(47, 111, 159, 0.22);
    --cv-gold: #d89b00;
    --cv-silver: #9a9a9a;
    --cv-orange: #ff8c00;
    --cv-border: #e5e7eb;
    --cv-shadow: 0 4px 14px rgba(15, 23, 42, 0.08);
  }

  html.dark,
  body.dark,
  [data-theme="dark"],
  .dark-theme,
  .theme--dark {
    --cv-card-bg: rgba(35, 35, 35, 0.60);
    --cv-border: rgba(220, 220, 220, 0.18);
    --cv-muted: #b8b8b8;
    --cv-strong: #f1f1f1;
    --cv-text: #e5e7eb;
    --cv-accent: #8cc8ff;
    --cv-card-bg: #1f2937;
    --cv-pill-bg: rgba(140, 200, 255, 0.12);
    --cv-pill-border: rgba(140, 200, 255, 0.30);
    --cv-gold: #ffb000;
    --cv-silver: #c6c6c6;
    --cv-orange: #ff9d2e;
  }

  .cv-wrap {
    max-width: 900px;
  }

  .cv-lead {
    margin: 0 0 1.2rem 0;
    color: var(--cv-muted);
    font-size: 0.98rem;
    line-height: 1.65;
  }

  .cv-section {
    margin: 1.65rem 0 0.85rem 0;
  }

  .cv-section-title {
    margin: 0 0 0.65rem 0;
    padding-bottom: 0.35rem;
    border-bottom: 1px solid var(--cv-border);
    font-size: 1.25rem;
    font-weight: 700;
    color: var(--cv-strong);
    letter-spacing: 0.02em;
  }

  .cv-card {
    margin: 0.85rem 0;
    padding: 1rem 1.1rem;
    border: 1px solid var(--cv-border);
    border-radius: 12px;
    background: var(--cv-card-bg);
    color: var(--cv-text);
    box-shadow: var(--cv-shadow);
  }

  .cv-card.compact {
    padding: 0.85rem 1rem;
  }

  .cv-card-title {
    margin: 0;
    font-size: 1.08rem;
    font-weight: 700;
    color: var(--cv-strong);
  }

  .cv-card-subtitle {
    margin: 0.25rem 0 0.35rem 0;
    color: var(--cv-muted);
    font-size: 0.95rem;
    line-height: 1.45;
  }

  .cv-meta {
    margin: 0.35rem 0 0.6rem 0;
    color: var(--cv-muted);
    font-size: 0.92rem;
  }

  .cv-card p {
    margin: 0.45rem 0;
    line-height: 1.62;
  }

  .cv-card ul {
    margin: 0.45rem 0 0 1.15rem;
    padding-left: 0;
  }

  .cv-card li {
    margin: 0.18rem 0;
    line-height: 1.5;
  }

  .cv-row {
    display: grid;
    grid-template-columns: 1fr;
    gap: 0.85rem;
  }

  @media (min-width: 760px) {
    .cv-row.two {
      grid-template-columns: 1fr 1fr;
    }
  }

  .cv-tags {
    margin-top: 0.55rem;
  }

  .cv-tag {
    display: inline-block;
    margin: 0.18rem 0.25rem 0.18rem 0;
    padding: 0.16rem 0.48rem;
    border: 1px solid var(--cv-pill-border);
    border-radius: 999px;
    background: var(--cv-pill-bg);
    color: var(--cv-accent);
    font-size: 0.82rem;
    white-space: nowrap;
  }

  .cv-gold {
    color: var(--cv-gold);
    font-weight: 700;
  }

  .cv-silver {
    color: var(--cv-silver);
    font-weight: 700;
  }

  .cv-orange {
    color: var(--cv-orange);
    font-weight: 700;
  }

  .cv-list-clean {
    list-style: none;
    margin-left: 0 !important;
  }

  .cv-list-clean li {
    margin: 0.45rem 0;
  }

  .cv-small {
    color: var(--cv-muted);
    font-size: 0.92rem;
  }
</style>

<div class="cv-wrap">

<p class="cv-lead">
My selected projects cover full-stack software engineering, computer architecture, artificial intelligence, and FPGA-based digital system design, reflecting both algorithmic problem solving and hands-on system implementation.
</p>

<section class="cv-section">
  <h2 class="cv-section-title">Projects</h2>

  <div class="cv-card">
    <h3 class="cv-card-title">Course Grading System</h3>
    <p class="cv-card-subtitle">CS304 Software Engineering, Spring 2025</p>
    <p>
      Developed a full-stack academic grading platform integrating code evaluation, handwritten assignment grading, attendance tracking, grading feedback, and dispute management. The system supports OCR-assisted processing of handwritten assignments and GPT-4o-based AI grading support, aiming to improve grading efficiency, feedback quality, and teacher-student communication in course management.
    </p>
    <ul>
      <li><strong>Tech stack:</strong> Vue.js, Express.js, PostgreSQL, OpenCV.js, Google Cloud Vision, GPT-4o (API).</li>
      <li><strong>GitHub Repository:</strong> <a href="https://github.com/sustech-cs304/team-project-25spring-team22">Course Grading System</a></li>
      <li><strong>Final Grade:</strong> 100/100</li>
    </ul>
  </div>

  <div class="cv-card">
    <h3 class="cv-card-title">Five-stage Pipeline CPU</h3>
    <p class="cv-card-subtitle">CS202 Computer Organization & Design, Spring 2025</p>
    <p>
      Designed and implemented a RISC-V32 CPU, including both single-cycle and five-stage pipeline architectures, and deployed the design on the EGO1 FPGA board. The pipelined version supports hazard handling, forwarding, stalling, branch prediction, and UART-based debugging. I also developed Python front-end tools for serial communication, register visualization, instruction decoding, and software-assisted branch prediction optimization, achieving stable execution of the pipelined CPU at up to 75 MHz.
    </p>
    <ul>
      <li><strong>Tech stack:</strong> Verilog, EGO1 FPGA, UART, Python.</li>
      <li><strong>GitHub Repository:</strong> <a href="https://github.com/Diaosi1317092/Computer-Organization-Project">Five-stage Pipeline CPU</a></li>
      <li><strong>Final Grade:</strong> 115/100</li>
    </ul>
  </div>

  <div class="cv-card">
    <h3 class="cv-card-title">Reversed-Reversi</h3>
    <p class="cv-card-subtitle">CS311 Artificial Intelligence (Honors), Spring 2025</p>
    <p>
      Implemented an AI agent for Reversed Reversi under strict platform constraints on time, memory, legality, and online round-robin competitiveness. The agent combines efficient move generation, board evaluation, and search/heuristic strategies for adversarial decision making in a modified Reversi setting, with computation optimized using NumPy and Numba. The final submission achieved <strong>Top 5 Player</strong> on the course competition platform.
    </p>
    <ul>
      <li><strong>Tech stack:</strong> Python, NumPy, Numba.</li>
      <li><strong>GitHub Repository:</strong> <a href="https://github.com/Diaosi1317092/Reversed-Reversi">Reversed-Reversi</a></li>
      <li><strong>Final Grade:</strong> 99/100</li>
    </ul>
  </div>

  <div class="cv-card">
    <h3 class="cv-card-title">Range Hood Program</h3>
    <p class="cv-card-subtitle">CS211 Digital Logic (Honors), Fall 2024</p>
    <p>
      Designed and implemented a range hood control system on FPGA, supporting power control, time display, fan-speed switching, countdown modes, self-cleaning, manual cleaning, lighting, and smart reminders. The system was built with modular Verilog state-machine design and integrated external devices including a 4×4 membrane keyboard for input and an LCD1602 display for real-time status and countdown output.
    </p>
    <ul>
      <li><strong>Tech stack:</strong> Verilog, EGO1 FPGA, 4×4 membrane keyboard, LCD1602.</li>
      <li><strong>GitHub Repository:</strong> <a href="https://github.com/Diaosi1317092/Digital-Logic-Project">Range Hood Program</a></li>
      <li><strong>Final Grade:</strong> 115/100</li>
    </ul>
  </div>
</section>

</div>
