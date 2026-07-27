---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
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
My publication work focuses on rigorous runtime analysis of randomized search heuristics and learning-based hyper-heuristics, with an emphasis on understanding when adaptive mechanisms provably improve optimization performance.
</p>

<section class="cv-section">
  <h2 class="cv-section-title">Conference Papers</h2>
  <p class="cv-lead">
  In Theoretical Computer Science, the authors are usually listed in alphabetical order.
  </p>
  <div class="cv-card">
    <h3 class="cv-card-title">On the Runtime Analysis of Reinforcement Learning Hyper-Heuristics</h3>
    <p class="cv-card-subtitle">
      Prof. Pietro S. Oliveto*, <strong>Zhenyu Wang</strong>, Peizhou Wu, and Mengqing Xu
    </p>
    <p class="cv-meta">
      Accepted to <strong>PPSN 2026</strong>, to appear in the proceedings. CCF-B Conference.
    </p>
    <ul>
      <details>
        <summary>Abstract</summary>
Selection Hyper-heuristics (HHs) automate algorithmic design by selecting from a set of low-level heuristics which one to apply at each stage of the optimisation process. Several impressive results have been recently rigorously proven regarding the performance of selection hyper-heuristics (HHs) for standard benchmark functions. However, the learning mechanisms employed by these HHs are considerably simplified compared to the machine learning techniques typically employed in real world applications.
        
In this paper we analyse a Reinforcement Learning Hyper-heuristic (RLHH) from the literature. The only previous result available proved that for a wide range of parameter settings, RLHH does not learn to select parameters appropriately for the standard LeadingOnes benchmark function. In this paper we rigorously prove that with appropriate parameter values RLHH equipped with two random local search operators, RLS₁ and RLS₂ optimises the benchmark function in the best possible expected runtime achievable with the two operators up to lower order terms.
        
Experiments show that for realistic problem sizes it is faster than the Generalised Random Gradient HH which was previously proven to also have optimal runtime up to lower order terms.

      </details>
    </ul>
  <div class="cv-tags">
      <span class="cv-tag">[arXiv](https://arxiv.org/pdf/2607.22036)</span>
    </div>
  </div>
</section>

</div>
