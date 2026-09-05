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
  :root {
    /* light mode */
    --cv-card-bg: #ffffff;
    --cv-border: #e5e7eb;
    --cv-muted: #666666;
    --cv-strong: #222222;
    --cv-text: #333333;
    --cv-accent: #2f6f9f;
    --cv-pill-bg: rgba(47, 111, 159, 0.10);
    --cv-pill-border: rgba(47, 111, 159, 0.22);
    --cv-gold: #d89b00;
    --cv-silver: #8f8f8f;
    --cv-orange: #ff8c00;
    --cv-shadow: 0 4px 14px rgba(15, 23, 42, 0.08);
  }
  
  /* dark mode: neutral gray, matching the original #313131 style */
  html.dark,
  body.dark,
  [data-theme="dark"],
  .dark-theme,
  .theme--dark {
    --cv-card-bg: #313131;
    --cv-border: #474747;
    --cv-muted: #c7c7c7;
    --cv-strong: #f4f4f4;
    --cv-text: #e0e0e0;
    --cv-accent: #9ecbff;
    --cv-pill-bg: rgba(158, 203, 255, 0.12);
    --cv-pill-border: rgba(158, 203, 255, 0.36);
    --cv-gold: #ffb000;
    --cv-silver: #d0d0d0;
    --cv-orange: #ff9d2e;
    --cv-shadow: none;
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
This page summarizes my education, research experience, selected academic activities, competitive programming experience, teaching, and technical skills.
</p>

<section class="cv-section">
  <h2 class="cv-section-title">Education</h2>

  <div class="cv-card compact">
    <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 6px;">
      <span class="cv-card-title">B.S. in Computer Science and Technology <span class="cv-small">(Turing Class)</span></span>
      <span style="white-space: nowrap; margin-left: 12px;">2023 – Present</span>
    </div>
    <p class="cv-card-subtitle">Southern University of Science and Technology</p>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Research Interests & Experience</h2>

  <p class="cv-lead">
    My research interests include randomized algorithms, algorithms and complexity, probabilistic analysis of algorithms, and the theoretical foundations of randomized search heuristics.
  </p>

  <div class="cv-card">
    <h3 class="cv-card-title">Research Assistant</h3>
    <p class="cv-card-subtitle">
      LIX – Laboratoire d’informatique de l’École polytechnique, École Polytechnique
    </p>
    <p class="cv-meta">Fall 2026 · Supervisor: Professor Benjamin Doerr</p>

    <p>
      Working on the theoretical analysis of multi-objective evolutionary algorithms and randomized search heuristics.
    </p>
    <p>
      Characterizing how population dynamics and selection mechanisms determine the progress of the underlying randomized search process.
    </p>
    <p>
      Establishing runtime bounds and identifying algorithmic or parameter regimes that yield provably improved asymptotic performance.
    </p>

    <div class="cv-tags">
      <span class="cv-tag">Multi-Objective Evolutionary Algorithms</span>
      <span class="cv-tag">Randomized Search Heuristics</span>
      <span class="cv-tag">Population Dynamics</span>
      <span class="cv-tag">Runtime Analysis</span>
    </div>
  </div>

  <div class="cv-card">
    <h3 class="cv-card-title">Research Assistant</h3>
    <p class="cv-card-subtitle">
      Theory of AI Lab, Southern University of Science and Technology
    </p>
    <p class="cv-meta">Spring 2025 · Supervisor: Professor Pietro S. Oliveto</p>

    <p>
      Conducted runtime analysis of hyper-heuristics, studying when learning-based selection mechanisms can identify the most effective search operators at different stages of an optimization process.
    </p>
    <p>
      Analyzed parameter adaptation and operator-selection dynamics on Pseudo-Boolean functions, using drift analysis, concentration inequalities, martingales, and stochastic-process techniques to establish asymptotic performance guarantees.
    </p>
    <p>
      This work resulted in publications at PPSN 2026 and a manuscript under review at AAAI 2027.
    </p>

    <div class="cv-tags">
      <span class="cv-tag">Hyper-Heuristics</span>
      <span class="cv-tag">Adaptive Operator Selection</span>
      <span class="cv-tag">Drift Analysis</span>
      <span class="cv-tag">Stochastic Processes</span>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Competitive Programming</h2>

  <div class="cv-card compact">
    <p>
      I have been deeply involved in competitive programming, both as a contestant and a problem setter, and have received several awards in algorithmic competitions.
    </p>
    <p>
      I am an <span class="cv-orange">International Master</span> on Codeforces (Max Rating 2314).
    </p>
  </div>

  <div class="cv-card compact">
    <h3 class="cv-card-title">Awards</h3>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">The 49th ICPC Hangzhou Regional Contest</span>
      <span class="cv-gold" style="white-space: nowrap; margin-left: 12px;">Gold Medal</span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">The 10th CCPC Zhengzhou Regional Contest</span>
      <span class="cv-gold" style="white-space: nowrap; margin-left: 12px;">Gold Medal</span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">The 49th ICPC Shenyang Regional Contest</span>
      <span class="cv-silver" style="white-space: nowrap; margin-left: 12px;">Silver Medal</span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">The 49th ICPC Asia East Continent Final Contest</span>
      <span class="cv-silver" style="white-space: nowrap; margin-left: 12px;">Silver Medal</span>
    </div>
  </div>

  <div class="cv-card compact">
    <h3 class="cv-card-title">Problem Setting</h3>
    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">The 3rd Universal Cup Finals</span>
      <span style="white-space: nowrap; margin-left: 12px;">Problem Setter</span>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Selected Coursework</h2>

  <div class="cv-card compact">
    <h3 class="cv-card-title">Overall Average Mark: <span class="cv-small">89.93/100</span></h3>

    <h3 class="cv-card-title"GPA: <span class="cv-small">3.7/4.0</span></h3>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">CS217 Data Structures and Algorithm Analysis (Honors)</span>
      <span style="white-space: nowrap; margin-left: 12px;">Fall 2024 — 100/100</span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">CS216 Algorithm Design and Analysis (Honors)</span>
      <span style="white-space: nowrap; margin-left: 12px;">Spring 2025 — 99/100</span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">CS342 Optimization Methods</span>
      <span style="white-space: nowrap; margin-left: 12px;">Spring 2026 — 100/100</span>
    </div>

    <p class="cv-card-subtitle">CS215 Discrete Mathematics (Honors)</p>
    <p class="cv-card-subtitle">CS338 Introduction to Theory of Computation</p>
    <p class="cv-card-subtitle">STA219 Probability and Statistics for Engineering</p>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Teaching</h2>

  <div class="cv-card compact">
    <p>
      Assisted with tutorials, grading, and student support for an honors-level algorithms course.
    </p>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <span class="cv-card-subtitle">CS217 Data Structures and Algorithm Analysis (Honors)</span>
      <span style="white-space: nowrap; margin-left: 12px;">Teaching Assistant · Fall 2025</span>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Skills</h2>

  <div class="cv-row two">
    <div class="cv-card compact">
      <h3 class="cv-card-title">Programming</h3>
      <div class="cv-tags">
        <span class="cv-tag">Modern C++</span>
        <span class="cv-tag">Python</span>
        <span class="cv-tag">Rust</span>
        <span class="cv-tag">Verilog</span>
        <span class="cv-tag">JavaScript</span>
      </div>
    </div>
    <div class="cv-card compact">
      <h3 class="cv-card-title">Languages</h3>
      <div class="cv-tags">
        <span class="cv-tag">Chinese: Native</span>
        <span class="cv-tag">English: 100/120 TOEFL iBT</span>
      </div>
    </div>
  </div>
</section>

</div>
