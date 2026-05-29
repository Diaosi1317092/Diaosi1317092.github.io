---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Conference Papers

### On the Runtime Analysis of Reinforcement Learning Hyper-Heuristics

Prof. Pietro S. Oliveto*, **Zhenyu Wang**, Peizhou Wu, and Mengqing Xu  
Accepted to PPSN 2026. To appear in the proceedings.
CCF-B Conference  

\* Corresponding author.  
**Zhenyu Wang**: Co-first author for the theory track.

<details>
<summary>Abstract</summary>

Selection Hyper-heuristics (HHs) automate algorithmic design by selecting from a set of low-level heuristics which one to apply at each stage of the optimisation process. Several impressive results have been recently rigorously proven regarding the performance of selection hyper-heuristics (HHs) for standard benchmark functions. However, the learning mechanisms employed by these HHs are considerably simplified compared to the machine learning techniques typically employed in real world applications.

In this paper we analyse a Reinforcement Learning Hyper-heuristic (RLHH) from the literature. The only previous result available proved that for a wide range of parameter settings, RLHH does not learn to select parameters appropriately for the standard LeadingOnes benchmark function. In this paper we rigorously prove that with appropriate parameter values RLHH equipped with two random local search operators, RLS₁ and RLS₂ optimises the benchmark function in the best possible expected runtime achievable with the two operators up to lower order terms.

Experiments show that for realistic problem sizes it is faster than the Generalised Random Gradient HH which was previously proven to also have optimal runtime up to lower order terms.

</details>
