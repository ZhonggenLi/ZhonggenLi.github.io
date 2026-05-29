---
permalink: /
title: "Zhonggen Li"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .home-page {
    --home-accent: #2f5fb3;
    --home-accent-soft: #eef4ff;
    --home-accent-border: #9fb7e7;
    --home-border: #e6e8ef;
    --home-muted: #5f6673;
    --home-text: #252a31;
    --home-panel: #ffffff;
    --home-highlight: #fff4cf;
    --home-highlight-border: #e0b536;
    --home-highlight-text: #715000;
  }

  html[data-theme="dark"] .home-page {
    --home-accent: #8fb6ff;
    --home-accent-soft: #1f2c42;
    --home-accent-border: #5f7fb8;
    --home-border: #384250;
    --home-muted: #b6beca;
    --home-text: #eef2f7;
    --home-panel: #161b22;
    --home-highlight: #3b3016;
    --home-highlight-border: #9d7a20;
    --home-highlight-text: #ffe09a;
  }

  .home-page h2 {
    border-bottom: 1px solid var(--home-border);
    padding-bottom: 0.35rem;
    margin-top: 2rem;
  }

  .home-intro {
    border-left: 4px solid var(--home-accent);
    padding: 0.15rem 0 0.15rem 1rem;
    margin-bottom: 1.6rem;
  }

  .interest-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.85rem;
    margin: 1rem 0 1.2rem;
  }

  .interest-item {
    background: var(--home-panel);
    border: 1px solid var(--home-border);
    border-radius: 8px;
    padding: 0.85rem 0.95rem;
  }

  .interest-item strong {
    color: var(--home-text);
    display: block;
    margin-bottom: 0.3rem;
  }

  .interest-item p {
    color: var(--home-muted);
    font-size: 0.92em;
    line-height: 1.55;
    margin: 0;
  }

  .publication-year {
    color: var(--home-muted);
    font-size: 1rem;
    letter-spacing: 0;
    margin: 1.4rem 0 0.65rem;
  }

  .publication-list {
    display: grid;
    gap: 0.9rem;
    margin-bottom: 1.2rem;
  }

  .publication-item {
    border-left: 3px solid var(--home-border);
    padding: 0.15rem 0 0.15rem 0.9rem;
  }

  .publication-item.featured {
    border-left-color: var(--home-highlight-border);
    background: linear-gradient(90deg, var(--home-highlight), transparent 68%);
    padding: 0.75rem 0.9rem;
    border-radius: 8px;
  }

  .publication-heading {
    display: block;
    line-height: 1.45;
    margin-bottom: 0.25rem;
  }

  .venue-badge,
  .award-badge,
  .rank-badge {
    border-radius: 999px;
    display: inline-flex;
    align-items: center;
    font-size: 0.75rem;
    font-weight: 700;
    line-height: 1;
    padding: 0.28rem 0.55rem;
    white-space: nowrap;
  }

  .venue-badge {
    color: #fff;
    margin-right: 0.35rem;
    vertical-align: baseline;
  }

  .venue-preprint { background: #6b7280; }
  .venue-vldb { background: #7c3aed; }
  .venue-jos { background: #2f855a; }
  .venue-sigmod { background: #4169e1; }
  .venue-icde { background: #b7791f; }

  .award-badge {
    background: var(--home-highlight);
    border: 1px solid var(--home-highlight-border);
    color: var(--home-highlight-text);
    margin-left: 0.35rem;
    vertical-align: baseline;
  }

  .rank-badge {
    background: var(--home-accent-soft);
    border: 1px solid var(--home-accent-border);
    color: var(--home-accent);
    margin-left: 0.25rem;
    vertical-align: baseline;
  }

  .publication-title {
    color: var(--home-text);
    display: inline;
    font-weight: 700;
  }

  .publication-item .publication-authors {
    color: var(--home-muted);
    font-size: 0.94em;
    line-height: 1.45;
    margin: 0.15rem 0 0;
  }

  .publication-item .publication-links {
    font-size: 0.9em;
    line-height: 1.35;
    margin: 0.12rem 0 0;
  }

  .compact-list {
    margin-top: 0.6rem;
  }

  .compact-list li {
    margin-bottom: 0.35rem;
  }

  @media (max-width: 720px) {
    .interest-grid {
      grid-template-columns: 1fr;
    }

    .publication-item.featured {
      padding: 0.7rem 0.75rem;
    }
  }
</style>

<div class="home-page" markdown="1">


I am a third-year Ph.D. student in the College of Computer Science and Technology at Zhejiang University (ZJU), advised by Prof. [Yunjun Gao](https://person.zju.edu.cn/gaoyj_cn). I received my B.E. degree from Harbin Institute of Technology (HIT) in June 2023, advised by Prof. [Hongzhi Wang](https://homepage.hit.edu.cn/wang) and Prof. [Xiaoou Ding](https://homepage.hit.edu.cn/dingxiaoou).


## Research Interests

My research focuses on **AI and data systems** through the lens of **software-hardware co-design**, with a particular emphasis on co-optimizing algorithms with hardware such as CPUs, GPUs, NPUs, and NVMe SSDs.

<div class="interest-grid">
  <div class="interest-item">
    <strong>Data Infrastructure for AI</strong>
    <p>Algorithms and systems for vector data management, memory-augmented AI systems, and retrieval-augmented generation (RAG), targeting both cloud and edge environments.</p>
  </div>
  <div class="interest-item">
    <strong>Efficient LLM Systems</strong>
    <p>Efficient training and inference for large language models, and system-level optimization for agentic AI and embodied intelligence applications.</p>
  </div>
</div>

I am open to collaborations and internship opportunities in **AI infrastructure** and **efficient LLM training & inference**. Please feel free to contact me via [email](mailto:zglics@gmail.com).

## <span id="publications">Publications</span>

### <span class="publication-year">2026</span>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge venue-preprint">Preprint</span>
      <span class="publication-title">A GPU-Accelerated Framework for Multi-Attribute Range-Filtered Approximate Nearest Neighbor Search</span>
    </div>
    <p class="publication-authors"><strong>Zhonggen Li</strong>, Haoran Yu, Zixuan Xu, Yifan Zhu, Yunjun Gao.</p>
    <p class="publication-links">[ <a href="https://arxiv.org/pdf/2604.20121">Paper</a> | <a href="https://github.com/ZJU-DAILY/Garfield">Code</a> ]</p>
  </article>

  <article class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge venue-vldb">VLDB J.</span>
      <span class="publication-title">Efficient Graph Embedding at Scale: Optimizing CPU-GPU-SSD Integration</span>
    </div>
    <p class="publication-authors"><strong>Zhonggen Li</strong>, Xiangyu Ke, Yifan Zhu, Yunjun Gao, Feifei Li.</p>
    <p class="publication-links">[ <a href="https://link.springer.com/article/10.1007/s00778-026-00974-8">Paper</a> | <a href="https://github.com/ZJU-DAILY/Legend">Code</a> ]</p>
  </article>

  <article class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge venue-sigmod">SIGMOD</span>
      <span class="publication-title">Scalable Graph Indexing Using GPUs for Approximate Nearest Neighbor Search</span>
      <span class="award-badge">Accepted without Revision (4/1049)</span>
      <!-- <span class="rank-badge">4 / 1049</span> -->
    </div>
    <p class="publication-authors"><strong>Zhonggen Li</strong>, Xiangyu Ke, Yifan Zhu, Bocheng Yu, Baihua Zheng, Yunjun Gao.</p>
    <p class="publication-links">[ <a href="https://dl.acm.org/doi/abs/10.1145/3769825">Paper</a> | <a href="https://github.com/ZJU-DAILY/Tagore">Code</a> ]</p>
  </article>

  <article class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge venue-jos">JoS</span>
      <span class="publication-title">GPU-Accelerated Clustering Algorithm for High-Dimensional Vectors (in Chinese)</span>
    </div>
    <p class="publication-authors"><strong>Zhonggen Li</strong>, Shenghao Gong, Haoran Yu, Yifan Zhu, Qing Liu, Yunjun Gao.</p>
    <p class="publication-links">[ <a href="https://www.jos.org.cn/jos/article/abstract/7512">Paper</a> ]</p>
  </article>
</div>

### <span class="publication-year">2025</span>

<div class="publication-list">
<article class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge venue-preprint">Preprint</span>
      <span class="publication-title">All-in-One Graph-Based Indexing for Hybrid Search on GPUs</span>
    </div>
    <p class="publication-authors"><strong>Zhonggen Li</strong>, Yougen Li, Yifan Zhu, Congcong Ge, Zhaoqiang Chen, Yunjun Gao.</p>
    <p class="publication-links">[ <a href="https://arxiv.org/pdf/2511.00855">Paper</a> | <a href="https://github.com/ZJU-DAILY/Allan-Poe">Code</a> ]</p>
  </article>

  <article class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge venue-icde">ICDE</span>
      <span class="publication-title">Accelerating Sparse Matrix-Matrix Multiplication for Graphs with Hybrid GPU Cores</span>
    </div>
    <p class="publication-authors"><strong>Zhonggen Li</strong>, Xiangyu Ke, Yifan Zhu, Yunjun Gao, Yaofeng Tu.</p>
    <p class="publication-links">[ <a href="https://www.computer.org/csdl/proceedings-article/icde/2025/360300a501/26FZzgVYoQo">Paper</a> | <a href="https://github.com/ZJU-DAILY/HC-SpMM">Code</a> ]</p>
  </article>
</div>

### <span class="publication-year">2024</span>

<div class="publication-list">
  <article class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge venue-icde">ICDE</span>
      <span class="publication-title">Accelerating Biclique Counting on GPUs</span>
    </div>
    <p class="publication-authors">Linshan Qiu, <strong>Zhonggen Li</strong>, Xiangyu Ke, Lu Chen, Yunjun Gao.</p>
    <p class="publication-links">[ <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10598058">Paper</a> | <a href="https://github.com/ZJU-DAILY/GBC">Code</a> ]</p>
  </article>
</div>

## <span id="awards">Honors & Awards</span>

<ul class="compact-list">
  <li>Outstanding Graduate of Harbin Institute of Technology, 2023.</li>
  <li>National Scholarship, 2020.</li>
  <li>First-Class Scholarship, 2019 - 2022.</li>
</ul>

## Education

<ul class="compact-list">
  <li><em>2023.09 - Present</em>, Ph.D., Zhejiang University. Supervisor: Prof. Yunjun Gao.</li>
  <li><em>2019.09 - 2023.06</em>, B.E., Harbin Institute of Technology. Supervisors: Prof. Hongzhi Wang and Prof. Xiaoou Ding.</li>
</ul>

</div>
