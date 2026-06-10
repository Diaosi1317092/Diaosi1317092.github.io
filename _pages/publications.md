---
layout: archive
title: "Publications"
permalink: /publications/
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
My publication work focuses on rigorous runtime analysis of randomized search heuristics and learning-based hyper-heuristics, with an emphasis on understanding when adaptive mechanisms provably improve optimization performance.
</p>

<section class="cv-section">
  <h2 class="cv-section-title">Conference Papers</h2>

  <div class="cv-card">
    <h3 class="cv-card-title">On the Runtime Analysis of Reinforcement Learning Hyper-Heuristics</h3>
    <p class="cv-card-subtitle">
      Prof. Pietro S. Oliveto*, <strong>Zhenyu Wang</strong>, Peizhou Wu, and Mengqing Xu
    </p>
    <p class="cv-meta">
      Accepted to <strong>PPSN 2026</strong>, to appear in the proceedings. <strong>CCF-B Conference.</strong>
    </p>
    <ul>
      <li>* Corresponding author.</li>
      <li><strong>Zhenyu Wang</strong>: Co-first author for the theory track.</li>
      <details>
        <summary>Abstract</summary>
Selection Hyper-heuristics (HHs) automate algorithmic design by selecting from a set of low-level heuristics which one to apply at each stage of the optimisation process. Several impressive results have been recently rigorously proven regarding the performance of selection hyper-heuristics (HHs) for standard benchmark functions. However, the learning mechanisms employed by these HHs are considerably simplified compared to the machine learning techniques typically employed in real world applications.
        
In this paper we analyse a Reinforcement Learning Hyper-heuristic (RLHH) from the literature. The only previous result available proved that for a wide range of parameter settings, RLHH does not learn to select parameters appropriately for the standard LeadingOnes benchmark function. In this paper we rigorously prove that with appropriate parameter values RLHH equipped with two random local search operators, RLS₁ and RLS₂ optimises the benchmark function in the best possible expected runtime achievable with the two operators up to lower order terms.
        
Experiments show that for realistic problem sizes it is faster than the Generalised Random Gradient HH which was previously proven to also have optimal runtime up to lower order terms.

      </details>
    </ul>
  </div>
</section>

</div>
