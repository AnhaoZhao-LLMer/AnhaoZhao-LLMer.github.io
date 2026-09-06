---
layout: profile
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<section id="research" class="profile-section research-section" aria-labelledby="research-title" markdown="1">

<h2 id="research-title">Research</h2>

My research focuses on **LLM post-training** and **LLM efficiency**, with the long-term goal of building general-purpose models that advance **reasoning, interaction, and inference efficiency**.

<div class="research-grid" markdown="1">

<div class="research-direction" markdown="1">

### LLM post-training

I study how supervised fine-tuning (SFT), reinforcement learning (RL), and on-policy distillation (OPD) can develop stronger reasoning and agentic capability. My work explores SFT on self-generated data for efficient reasoning [[On-Policy SFT](https://arxiv.org/abs/2602.13407)], RL for adaptive streaming reasoning [[AdaSR](https://arxiv.org/abs/2606.14694)], and more stable and effective OPD [[PowerOPD](https://arxiv.org/abs/2606.17199), [KL Agreement Trap](https://arxiv.org/abs/2606.09471)].

</div>

<div class="research-direction" markdown="1">

### LLM efficiency

I explore efficiency at both the **token** and **architecture** levels. At the token level, I study alternatives to explicit reasoning tokens [[Latent CoT Survey](https://arxiv.org/abs/2505.16782)] and reasoning while reading to reduce response latency [[StreamingThinker](https://arxiv.org/abs/2510.17238)]. At the architecture level, I investigate token-adaptive computation [[SkipGPT](https://arxiv.org/abs/2506.04179)], the practical inference speedups of model pruning [[Beyond FLOPs](https://arxiv.org/abs/2606.09080)], and visual cache reuse and sparse interactions for efficient multimodal inference [[miniReranker](https://arxiv.org/abs/2606.10759)].

</div>

</div>

<div class="collaboration-note" markdown="1">

📬*I am open to collaborations and discussions. Please feel free to reach out to me if you are interested in my research or any relevant topics.*

</div>

</section>

<section id="news" class="profile-section" aria-labelledby="news-title">
<h2 id="news-title">News</h2>
<div class="news-list">
<div class="news-row">
<time datetime="2026-09">2026.09</time>
<div markdown="1">

Five papers accepted to EMNLP 2026: **3 Main Conference papers** and **2 Findings papers** 🎉!

</div>
</div>
<div class="news-row">
<time datetime="2026-05">2026.05</time>
<div markdown="1">

Got one paper accepted by ICML 2026🎉!

</div>
</div>
<div class="news-row">
<time datetime="2026-02">2026.02</time>
<div markdown="1">

Got one paper accepted by CVPR 2026 **Spotlight**🎉!

</div>
</div>
<div class="news-row">
<time datetime="2026-01">2026.01</time>
<div markdown="1">

Got one paper accepted by ICLR 2026🎉!

</div>
</div>
</div>
<details class="older-news">
<summary>Earlier news</summary>
<div class="news-list">
<div class="news-row">
<time datetime="2025-11">2025.11</time>
<div markdown="1">

Attended EMNLP 2025 in person for the first time — a truly exciting experience 🎉

</div>
</div>
<div class="news-row">
<time datetime="2025-09">2025.09</time>
<div markdown="1">

Started my Ph.D. study at the [NLP Group @ PolyU](https://polyunlp.github.io/) & [EIT NLP](https://eit-nlp.github.io/lab-website/), supervised by Dr. Xiaoyu Shen and Prof. Wenjie Li.

</div>
</div>
<div class="news-row">
<time datetime="2025-08">2025.08</time>
<div markdown="1">

Got one paper accepted by EMNLP 2025🎉!

</div>
</div>
<div class="news-row">
<time datetime="2025-05">2025.05</time>
<div markdown="1">

Released our new [survey](https://arxiv.org/pdf/2505.16782) on Latent Chain-of-Thought Reasoning.

</div>
</div>
<div class="news-row">
<time datetime="2025-05">2025.05</time>
<div markdown="1">

Got one paper accepted by ACL 2025🎉!

</div>
</div>
<div class="news-row">
<time datetime="2025-05">2025.05</time>
<div markdown="1">

Got one paper accepted by ICML 2025🎉!

</div>
</div>
<div class="news-row">
<time datetime="2024-09">2024.09</time>
<div markdown="1">

Got one paper accepted by EMNLP 2024🎉!

</div>
</div>
</div>
</details>
</section>

<section id="publications" class="profile-section" aria-labelledby="publications-title" markdown="1">

<h2 id="publications-title">Publications</h2>

<div class="publication-intro" markdown="1">

Most recent publications on [Google Scholar](https://scholar.google.com.hk/citations?user=19oxcOwAAAAJ&hl=zh-CN&oi=ao).  
\* indicates equal contribution

</div>

<h3 class="publication-group-title">Conference &amp; Journal Papers</h3>

<article class="publication">
<div class="publication-venue" aria-label="EMNLP 2026 Main"><span>EMNLP</span><small>2026 · Main</small></div>
<div class="publication-body" markdown="1">

### Beyond FLOPs: Benchmarking Real Inference Acceleration of LLM Pruning under a GEMM-Centric Taxonomy

Haozhe Hu, Hao Wu, **<ins>Anhao Zhao</ins>**, Longwei Ding, Peiran Yin, Yunpu Ma, Xiaoyu Shen

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/abs/2606.09080) [Code](https://github.com/EIT-NLP/LLM-Pruning/tree/main/PruningInferSim)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="EMNLP 2026 Main"><span>EMNLP</span><small>2026 · Main</small></div>
<div class="publication-body" markdown="1">

### PowerOPD: Stabilizing On-Policy Distillation with Bounded Power Transformation

**<ins>Anhao Zhao</ins>**, Junlong Tong, Yingqi Fan, Ping Nie, Wenjie Li, Xiaoyu Shen

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/abs/2606.17199) [Code](https://github.com/EIT-NLP/PowerOPD)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="EMNLP 2026 Main"><span>EMNLP</span><small>2026 · Main</small></div>
<div class="publication-body" markdown="1">

### Escaping the KL Agreement Trap in On-Policy Distillation

Haoran Xin, **<ins>Anhao Zhao</ins>**, Ying Sun, Jin Li, Xiaoyu Shen, Hui Xiong

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/abs/2606.09471)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Findings of EMNLP 2026"><span>EMNLP</span><small>2026 · Findings</small></div>
<div class="publication-body" markdown="1">

### Post-Training Shifts Confidence: A Three-Stage Analysis of How SFT, RL, and OPD Shape CoT Calibration

Shuhao Li, Guodong Du, **<ins>Anhao Zhao</ins>**, Wanyu Lin, Tianyu Yuan, Xiaoyu Shen

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/abs/2607.13753) [Repository](https://github.com/EIT-NLP/Post-Training-Calibration)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Findings of EMNLP 2026"><span>EMNLP</span><small>2026 · Findings</small></div>
<div class="publication-body" markdown="1">

### Reasoning Beyond Language: A Comprehensive Survey on Latent Chain-of-Thought Reasoning

Xinghao Chen\*, **<ins>Anhao Zhao</ins>**\*, Heming Xia, Xuan Lu, Hanlin Wang, Yanjun Chen, Wei Zhang, Jian Wang†, Wenjie Li, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2505.16782) [Code](https://github.com/EIT-NLP/Awesome-Latent-CoT)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="CVPR 2026"><span>CVPR</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### What Do Visual Tokens Really Encode? Uncovering Sparsity and Redundancy in Multimodal Large Language Models

Yingqi Fan, Junlong Tong, **<ins>Anhao Zhao</ins>**, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2603.00510) [Code](https://github.com/EIT-NLP/EmbedLens)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="ICLR 2026"><span>ICLR</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### StreamingThinker: Large Language Models Can Think While Reading

Junlong Tong, Yingqi Fan, **<ins>Anhao Zhao</ins>**, Yunpu Ma, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2510.17238) [Code](https://github.com/EIT-NLP/StreamingLLM)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="EMNLP 2025 Main"><span>EMNLP</span><small>2025 · Main</small></div>
<div class="publication-body" markdown="1">

### VisiPruner: Decoding Discontinuous Cross-Modal Dynamics for Efficient Multimodal LLMs

Yingqi Fan, **<ins>Anhao Zhao</ins>**, Jinlan Fu, Junlong Tong, Hui Su, Yijie Pan, Wei Zhang, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://aclanthology.org/2025.emnlp-main.955.pdf) [Code](https://github.com/EIT-NLP/VisiPruner)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Findings of ACL 2025"><span>ACL</span><small>2025 · Findings</small></div>
<div class="publication-body" markdown="1">

### LLM as Effective Streaming Processor: Bridging Streaming-Batch Mismatches with Group Position Encoding

Junlong Tong, Jinlan Fu, Zixuan Lin, Yingqi Fan, **<ins>Anhao Zhao</ins>**, Hui Su, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2505.16983) [Code](https://github.com/EIT-NLP/StreamingLLM)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="ICML 2025"><span>ICML</span><small>2025</small></div>
<div class="publication-body" markdown="1">

### SkipGPT: Each Token is One of a Kind

**<ins>Anhao Zhao</ins>**, Fanghua Ye†, Yingqi Fan, Junlong Tong, Jing Xiong, Zhiwei Fei, Hui Su, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://openreview.net/pdf?id=d7v2iUSa9s) [Code](https://github.com/EIT-NLP/SkipGPT)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="EMNLP 2024 Main"><span>EMNLP</span><small>2024 · Main</small></div>
<div class="publication-body" markdown="1">

### Unveiling In-Context Learning: A Coordinate System to Understand Its Working Mechanism

**<ins>Anhao Zhao</ins>**, Fanghua Ye, Jinlan Fu, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://aclanthology.org/2024.emnlp-main.689.pdf) [Code](https://github.com/EIT-NLP/2D-Coordinate-System-for-ICL)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Knowledge-Based Systems 2024"><span>KBS</span><small>2024</small></div>
<div class="publication-body" markdown="1">

### A dynamic multi-modal deep reinforcement learning framework for 3D bin packing problem

**<ins>Anhao Zhao</ins>**, Tianrui Li, Andrew Lim

<div class="publication-links" markdown="1">

[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705124006245) [Code](https://github.com/AnhaoZhao-LLMer/A_Dynamic_Multi-Modal_Deep_Reinforcement_Learning_Framework_for_3D_Bin_Packing_Problem)

</div>
</div>
</article>

<h3 class="publication-group-title">ArXiv Preprints</h3>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### AdaSR: Adaptive Streaming Reasoning with Hierarchical Relative Policy Optimization

Junlong Tong, Wenqi Xu, Yingqi Fan, **<ins>Anhao Zhao</ins>**, Xuan Lu, Yang Tan, Xiaoyu Shen

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/abs/2606.14694) [Repository](https://github.com/EIT-NLP/StreamingLLM/tree/main/AdaSR)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### miniReranker: Efficient Multimodal Reranking through Visual Cache Reuse and Interaction Sparsity

Yingqi Fan, Xuan Lu, **<ins>Anhao Zhao</ins>**, Junlong Tong, Ping Nie, Kai Zou, Yunpu Ma, Wei Zhang, Xiaoyu Shen

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/abs/2606.10759)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### ProactiveLLM: Learning Active Interaction for Streaming Large Language Models

Junlong Tong, Yao Zhang, **<ins>Anhao Zhao</ins>**, Yingqi Fan, Yunpu Ma, Xiaoyu Shen

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/abs/2606.00523) [Repository](https://github.com/EIT-NLP/StreamingLLM/tree/main/ProactiveLLM)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### Decoupling KL and Trajectories: A Unified Perspective for SFT, DAgger, Offline RL, and OPD in LLM Distillation

**<ins>Anhao Zhao</ins>**, H Xin, Yingqi Fan, Junlong Tong, Wenjie Li, Xiaoyu Shen

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2605.16826)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### SkipOPU: An FPGA-based Overlay Processor for Large Language Models with Dynamically Allocated Computation

Zicheng He, **<ins>Anhao Zhao</ins>**, Xiaoyu Shen, Chen Wu, Lei He

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2603.14785)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### On-Policy Supervised Fine-Tuning for Efficient Reasoning

**<ins>Anhao Zhao</ins>**, Ziyang Chen, Junlong Tong, Yingqi Fan, Fanghua Ye, Shuhao Li, Yunpu Ma, Wenjie Li, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2602.13407) [Code](https://github.com/EIT-NLP/On-Policy-SFT)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### ViCA: Efficient Multimodal LLMs with Vision-Only Cross-Attention

Wenjie Liu, Hao Wu, Xin Qiu, Yingqi Fan, Yihan Zhang, **<ins>Anhao Zhao</ins>**, Yunpu Ma, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2602.07574) [Code](https://github.com/EIT-NLP/ViCA)

</div>
</div>
</article>

<article class="publication">
<div class="publication-venue" aria-label="Arxiv 2026"><span>arXiv</span><small>2026</small></div>
<div class="publication-body" markdown="1">

### From LLMs to LRMs: Rethinking Pruning for Reasoning-Centric Models

Longwei Ding, **<ins>Anhao Zhao</ins>**, Fanghua Ye, Ziyang Chen, Xiaoyu Shen†

<div class="publication-links" markdown="1">

[Paper](https://arxiv.org/pdf/2601.18091) [Code](https://github.com/EIT-NLP/LRM-Pruning)

</div>
</div>
</article>

</section>

<section id="service" class="profile-section service-section" aria-labelledby="service-title" markdown="1">

<h2 id="service-title">Service</h2>

**Reviewer/Program Committee Member:**  
ICLR27, ICLR26, CVPR26, ECCV26, ICML26, NeurIPS26

**Teaching Assistant:**    
COMP1010_26271_C: Computational Thinking and Problem Solving  
COMP 5311: Internet Infrastructure and Protocols, Fall 2025, PolyU  
COMP 5532: DIGITAL TWINS & VIRTUAL HUMAN, Spring 2026, PolyU

</section>

<div class="visitor-map">{% include mapmyvisitors.html %}</div>
