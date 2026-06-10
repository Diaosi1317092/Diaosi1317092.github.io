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
    --cv-card-bg: rgba(255, 255, 255, 0.72);
    --cv-border: rgba(120, 120, 120, 0.22);
    --cv-muted: #666;
    --cv-strong: #222;
    --cv-accent: #2f6f9f;
    --cv-pill-bg: rgba(47, 111, 159, 0.10);
    --cv-pill-border: rgba(47, 111, 159, 0.22);
    --cv-gold: #d89b00;
    --cv-silver: #9a9a9a;
    --cv-orange: #ff8c00;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --cv-card-bg: rgba(35, 35, 35, 0.60);
      --cv-border: rgba(220, 220, 220, 0.18);
      --cv-muted: #b8b8b8;
      --cv-strong: #f1f1f1;
      --cv-accent: #8cc8ff;
      --cv-pill-bg: rgba(140, 200, 255, 0.12);
      --cv-pill-border: rgba(140, 200, 255, 0.30);
      --cv-gold: #ffb000;
      --cv-silver: #c6c6c6;
      --cv-orange: #ff9d2e;
    }
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
This page summarizes my education, research experience, selected academic activities, competitive programming experience, teaching, projects, and technical skills.
</p>

<section class="cv-section">
  <h2 class="cv-section-title">Education</h2>

  <div class="cv-card compact">
    <h3 class="cv-card-title">B.S. in Computer Science and Technology (Turing Class)</h3>
    <p class="cv-card-subtitle">Southern University of Science and Technology, 2023–Present</p>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Research Experience</h2>

  <div class="cv-card">
    <h3 class="cv-card-title">Research Assistant <span class="cv-small">(Expected)</span></h3>
    <p class="cv-card-subtitle">
      LIX – Laboratoire d’informatique de l’École polytechnique, École Polytechnique
    </p>
    <p class="cv-meta">Fall 2026 · Supervisor: Professor Benjamin Doerr</p>
    <p>
      Expected to work on the mathematical runtime analysis of randomized search heuristics and hyper-heuristics, with a focus on rigorous theoretical analysis of randomized optimization processes.
    </p>
    <p>
      Planned research directions include the behavior of hyper-heuristics on multimodal optimization problems, adaptive operator selection, phase transitions in heuristic performance, and more advanced runtime-analysis techniques.
    </p>
    <div class="cv-tags">
      <span class="cv-tag">Randomized Search Heuristics</span>
      <span class="cv-tag">Runtime Analysis</span>
      <span class="cv-tag">Hyper-Heuristics</span>
      <span class="cv-tag">Multimodal Optimization</span>
    </div>
  </div>

  <div class="cv-card">
    <h3 class="cv-card-title">Research Assistant</h3>
    <p class="cv-card-subtitle">
      Theory of AI Lab, Southern University of Science and Technology
    </p>
    <p class="cv-meta">Spring 2025 · Supervisor: Professor Pietro S. Oliveto</p>
    <p>
      Conducted theoretical research on randomized algorithms, reinforcement learning hyper-heuristics, and runtime analysis of learning-based selection mechanisms.
    </p>
    <p>
      Studied how parameter settings affect the ability of reinforcement learning hyper-heuristics to identify useful low-level heuristics during the optimization process, and developed formal runtime arguments using tools from drift analysis, probabilistic inequalities, and randomized search heuristic theory.
    </p>
    <div class="cv-tags">
      <span class="cv-tag">Theory of AI</span>
      <span class="cv-tag">Reinforcement Learning Hyper-Heuristics</span>
      <span class="cv-tag">Drift Analysis</span>
      <span class="cv-tag">Randomized Algorithms</span>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Competitive Programming</h2>

  <div class="cv-card compact">
    <p>
      I am an <span class="cv-orange">International Master</span> on Codeforces (Max Rating 2314).
    </p>
  </div>

  <div class="cv-card compact">
    <h3 class="cv-card-title">Awards</h3>
    <p class="cv-card-subtitle">The 49th International Collegiate Programming Contest Hangzhou Regional Contest</p>
    <ul>
      <li><span class="cv-gold">Gold Medal</span></li>
    </ul>
    <p class="cv-card-subtitle">The 10th China Collegiate Programming Contest Zhengzhou Regional Contest</p>
    <ul>
      <li><span class="cv-gold">Gold Medal</span></li>
    </ul>
    <p class="cv-card-subtitle">The 49th International Collegiate Programming Contest Shenyang Regional Contest</p>
    <ul>
      <li><span class="cv-silver">Silver Medal</span></li>
    </ul>
    <p class="cv-card-subtitle">The 49th International Collegiate Programming Contest East-Continent Finals</p>
    <ul>
      <li><span class="cv-silver">Silver Medal</span></li>
    </ul>
  </div>

  <div class="cv-card compact">
    <h3 class="cv-card-title">Problem Setting and Judging</h3>
    <p class="cv-card-subtitle">The 3rd Universal Cup Finals</p>
    <ul>
      <li>Problem Selection Committee Member</li>
      <li>Problem Setter</li>
    </ul>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Courses</h2>

  <div class="cv-card compact">
    <p><strong>Average Mark:</strong> 89.25/100</p>
    <ul>
      <li><strong>CS217 Data Structures and Algorithm Analysis (Honors)</strong>, Fall 2024 — Final Grade: 100/100</li>
      <li><strong>CS216 Algorithm Design and Analysis (Honors)</strong>, Spring 2025 — Final Grade: 99/100</li>
    </ul>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Teaching</h2>

  <div class="cv-card compact">
    <h3 class="cv-card-title">Teaching Assistant</h3>
    <p class="cv-card-subtitle">CS217 Data Structures and Algorithm Analysis (Honors), Fall 2025</p>
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
        <span class="cv-tag">English: Fluent</span>
      </div>
    </div>
  </div>
</section>

</div>
