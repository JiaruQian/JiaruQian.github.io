---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. candidate in Peking University, supervised by Prof. Ge Li. I completed my undergraduate studies in School of Computer Science in Wuhan University, where I ranked 1st out of 57. I have also been fortunate to begin my research journey under the supervision of Prof. Mang Ye in 2024.

My research interest includes code generation, formal verification and LLM reasoning.
I aspire to work on research that introduces genuinely new paradigms and challenges prevailing assumptions in both academia and industry.


# 🔥 News
- *2026.07*: &nbsp;🎉🎉 Paper **Saber** has been awarded ACL 2026 SAC Highlight Award.
- *2026.03*: &nbsp;🎉🎉 Paper **KOCO-Bench** has been accepted by ACL Main Conference 2026.
- *2025.09*: &nbsp;🎉🎉 Our survey paper has been accepted by Software Journal 2025.
- *2025.09*: &nbsp;🎉🎉 Paper **OASIS** has been accepted by NeurIPS 2025.
- *2025.05*: &nbsp;🎉🎉 Paper **GHOST** has been accepted by ICML 2025.

# 📝 Selected Publications

<div class="publication-card">
  <div class="publication-content">
    <span class="publication-venue">ICML 2025</span>
    <h3><a href="https://proceedings.mlr.press/v267/qian25a.html">GHOST: Generalizable One-Shot Federated Graph Learning with Proxy-Based Topology Knowledge Retention</a></h3>
    <p class="publication-authors"><strong>Jiaru Qian</strong>, Guancheng Wan, Wenke Huang, Guibin Zhang, Yuxin Wu, Bo Du, Mang Ye</p>
    <p class="publication-summary">Retains transferable topology knowledge through learnable proxies for generalizable one-shot federated graph learning.</p>
  </div>
  <a class="publication-figure" href="https://proceedings.mlr.press/v267/qian25a.html"><img src="/images/ICML25-GHOST.png" alt="Overview of the GHOST method"></a>
</div>

<div class="publication-card">
  <div class="publication-content">
    <span class="publication-venue">NeurIPS 2025</span>
    <h3><a href="https://papers.nips.cc/paper_files/paper/2025/hash/7300dd4d625cb42a438c1b822c77569f-Abstract-Conference.html">OASIS: One-Shot Federated Graph Learning via Wasserstein Assisted Knowledge Integration</a></h3>
    <p class="publication-authors">Frank Wan, <strong>Jiaru Qian</strong>, Wenke Huang, Qilin Xu, Xianda Guo, Boheng Li, Guibin Zhang, Bo Du, Mang Ye</p>
    <p class="publication-summary">Integrates semantic and structural knowledge with a topology codebook and Wasserstein-guided distillation.</p>
  </div>
  <a class="publication-figure" href="https://papers.nips.cc/paper_files/paper/2025/hash/7300dd4d625cb42a438c1b822c77569f-Abstract-Conference.html"><img src="/images/NeurIPS25-OASIS.png" alt="Overview of the OASIS method"></a>
</div>

<div class="publication-card">
  <div class="publication-content">
    <span class="publication-venue">Software Journal 2025</span>
    <h3><a href="https://arxiv.org/abs/2508.00083">A Survey on Code Generation with LLM-based Agents</a></h3>
    <p class="publication-authors">Yihong Dong, Xue Jiang, <strong>Jiaru Qian</strong>, Tian Wang, Kechi Zhang, Zhi Jin, Ge Li</p>
    <p class="publication-summary">Provides a systematic taxonomy of LLM-based code-generation agents and outlines key challenges and future directions.</p>
  </div>
  <a class="publication-figure" href="https://arxiv.org/abs/2508.00083"><img src="/images/LLMCodeAgentSurvey.png" alt="Taxonomy of LLM-based code generation agents"></a>
</div>

<div class="publication-card">
  <div class="publication-content">
    <span class="publication-venue">ACL 2026</span>
    <h3><a href="https://doi.org/10.18653/v1/2026.acl-long.1311">KOCO-Bench: Can Large Language Models Leverage Domain Knowledge in Software Development?</a></h3>
    <p class="publication-authors">Xue Jiang, Ge Li, <strong>Jiaru Qian</strong>, Xianjie Shi, Chenjie Li, Hao Zhu, Ziyu Wang, Jielun Zhang, Zeyu Zhao, Kechi Zhang, Jia Li, Wenpin Jiao, Zhi Jin, Yihong Dong</p>
    <p class="publication-summary">Benchmarks how well language models acquire and apply new domain knowledge in realistic software development.</p>
  </div>
  <a class="publication-figure" href="https://doi.org/10.18653/v1/2026.acl-long.1311"><img src="/images/ACL26-KOCOBENCH.png" alt="Overview of KOCO-Bench"></a>
</div>

<div class="publication-card">
  <div class="publication-content">
    <span class="publication-venue publication-venue--review">Under Review</span>
    <h3>Parallel Thinking for Language Model with Path Diversity</h3>
    <p class="publication-authors"><strong>Jiaru Qian</strong> <span class="author-note">· Co-First Author</span></p>
    <p class="publication-summary">Encourages diverse reasoning paths during reinforcement learning to prevent mode collapse in parallel thinking.</p>
  </div>
  <div class="publication-figure"><img src="/images/DPT.png" alt="Overview of diverse parallel thinking"></div>
</div>

<div class="publication-card">
  <div class="publication-content">
    <span class="publication-venue publication-venue--review">Under Review</span>
    <h3><a href="https://arxiv.org/abs/2605.15334">From I/O to Code with Discovery Agent</a></h3>
    <p class="publication-authors">Yihong Dong, <strong>Jiaru Qian</strong>, Haoran Zhang, Peixu Wang, Binhua Li, Zhi Jin, Yongbin Li, Ge Li, Xiaokang Yang, Xue Jiang</p>
    <p class="publication-summary">Introduces IO2Code and a discovery agent that synthesizes programs from input-output examples through curriculum evolution.</p>
  </div>
  <a class="publication-figure" href="https://arxiv.org/abs/2605.15334"><img src="/images/IO2Code.png" alt="Overview of IO2Code and its discovery agent"></a>
</div>

# 🎖 Honors and Awards
- *2026.06* Outstanding Graduate of Wuhan University
- *2026.05* Lei Jun Computer Science Breakthrough Scholarship, Wuhan University (CNY 50,000)
- *2022–2026* National Scholarship, awarded for three consecutive years (CNY 10,000 each)
- *2024.12* National Second Prize, China Undergraduate Mathematical Contest in Modeling

# 📖 Education
- *2026–2031*, Ph.D. in Computer Science, School of Computer Science, Peking University
- *2022–2026*, B.Eng. in Computer Science, School of Computer Science, Wuhan University
