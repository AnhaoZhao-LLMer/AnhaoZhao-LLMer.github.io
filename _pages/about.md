---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- ## About Me -->

I am **Anhao Zhao**, a joint Ph.D. student at the [NLP Group](https://polyunlp.github.io/) of The Hong Kong Polytechnic University & [EIT NLP](https://idt.eitech.edu.cn/nlp/#/) of Eastern Institute of Technology, Ningbo, fortunately supervised by Dr. [Xiaoyu Shen](https://chin-gyou.github.io//) and Prof. [Wenjie Li](https://www4.comp.polyu.edu.hk/~cswjli/). 

# Research

I am a long-termist, focusing on LLM efficiency with the goal of exploring the Pareto frontier between accuracy and deployment cost. My work centers on two complementary directions:

- **Model architecture and KV-cache efficiency (vertical perspective):** Aiming to reduce the per-token computational and memory cost. Recent work includes SkipGPT [[ICML'25](https://arxiv.org/pdf/2506.04179)], which proposes per-token adaptive activation of parameter subsets (token-aware gating), as well as strategies for selective KV-cache dropping [[EMNLP'25](https://openreview.net/pdf?id=eqSChk2Bx8)].

- **Token generation efficiency (horizontal perspective):** Reducing the average number of generated tokens. One recent line of work surveys latent reasoning as a promising paradigm for achieving more efficient chain-of-thought (CoT) reasoning [[arXiv'25](https://arxiv.org/pdf/2505.16782)]. Another line of work investigates early-answer generation strategies, where models can output responses before fully processing the input or completing reasoning steps [[ACL'25](https://arxiv.org/pdf/2505.16983)].

I believe that democratizing large language models (LLMs)—making them more accessible, affordable, and widely usable—requires progress along both of these axes. 

📬 *I am open to collaborations and discussions. Please feel free to reach out to me if you are interested in my research or any relevant topics.*

# News

[2025.11] Attended EMNLP 2025 in person for the first time — a truly exciting experience 🎉  
[2025.09] Started my Ph.D. study at the [NLP Group @ PolyU](https://polyunlp.github.io/) & [EIT NLP](https://eit-nlp.github.io/lab-website/), supervised by Dr. Xiaoyu Shen and Prof. Wenjie Li.  
[2025.08] Got one paper accepted by EMNLP 2025🎉!   
[2025.05] Released our new [survey](https://arxiv.org/pdf/2505.16782) on Latent Chain-of-Thought Reasoning.  
[2025.05] Got one paper accepted by ACL 2025🎉!  
[2025.05] Got one paper accepted by ICML 2025🎉!  
[2024.09] Got one paper accepted by EMNLP 2024🎉!  

# Publications

Most recent publications on [Google Scholar](https://scholar.google.com.hk/citations?user=19oxcOwAAAAJ&hl=zh-CN&oi=ao).  
\* indicates equal contribution
**From LLMs to LRMs: Rethinking Pruning for Reasoning-Centric Models**
Longwei Ding, **<ins>Anhao Zhao</ins>**, Fanghua Ye, Ziyang Chen, Xiaoyu Shen<sup>†</sup>
Arxiv 2026. [[link]](https://arxiv.org/pdf/2601.18091) [[code]](https://github.com/EIT-NLP/LRM-Pruning)  

**VisiPruner: Decoding Discontinuous Cross-Modal Dynamics for Efficient Multimodal LLMs**  
Yingqi Fan, **<ins>Anhao Zhao</ins>**, Jinlan Fu, Junlong Tong, Hui Su, Yijie Pan, Wei Zhang, Xiaoyu Shen<sup>†</sup>    
EMNLP 2025 Main. [[link]](https://aclanthology.org/2025.emnlp-main.955.pdf) [[code]](https://github.com/EIT-NLP/VisiPruner)  

**StreamingThinker: Large Language Models Can Think While Reading**  
Junlong Tong, Yingqi Fan, **<ins>Anhao Zhao</ins>**, Yunpu Ma, Xiaoyu Shen<sup>†</sup>   
ICLR 2026. [[link]](https://arxiv.org/pdf/2510.17238) [[code]](https://github.com/EIT-NLP/StreamingLLM) 

**Reasoning Beyond Language: A Comprehensive Survey on Latent Chain-of-Thought Reasoning**  
Xinghao Chen\*, **<ins>Anhao Zhao</ins>**\*, Heming Xia, Xuan Lu, Hanlin Wang, Yanjun Chen, Wei Zhang, Jian Wang<sup>†</sup>, Wenjie Li, Xiaoyu Shen<sup>†</sup>  
Arxiv 2025. [[link]](https://arxiv.org/pdf/2505.16782) [[code]](https://github.com/EIT-NLP/Awesome-Latent-CoT)  

**LLM as Effective Streaming Processor: Bridging Streaming-Batch Mismatches with Group Position Encoding**  
Junlong Tong, Jinlan Fu, Zixuan Lin, Yingqi Fan, **<ins>Anhao Zhao</ins>**, Hui Su, Xiaoyu Shen<sup>†</sup>  
Findings of ACL 2025. [[link]](https://arxiv.org/pdf/2505.16983) [[code]](https://github.com/EIT-NLP/StreamingLLM)  

**SkipGPT: Each Token is One of a Kind**  
**<ins>Anhao Zhao</ins>**, Fanghua Ye<sup>†</sup>, Yingqi Fan, Junlong Tong, Jing Xiong, Zhiwei Fei, Hui Su, Xiaoyu Shen<sup>†</sup>  
ICML 2025. [[link]](https://openreview.net/pdf?id=d7v2iUSa9s) [[code]](https://github.com/EIT-NLP/SkipGPT)  

**Unveiling In-Context Learning: A Coordinate System to Understand Its Working Mechanism**  
**<ins>Anhao Zhao</ins>**, Fanghua Ye, Jinlan Fu, Xiaoyu Shen<sup>†</sup>  
EMNLP 2024 Main. [[link]](https://aclanthology.org/2024.emnlp-main.689.pdf) [[code]](https://github.com/EIT-NLP/2D-Coordinate-System-for-ICL)  

**A dynamic multi-modal deep reinforcement learning framework for 3D bin packing problem**  
**<ins>Anhao Zhao</ins>**, Tianrui Li, Andrew Lim  
Knowledge-Based Systems 2024. [[link]](https://www.sciencedirect.com/science/article/abs/pii/S0950705124006245) [[code]](https://github.com/AnhaoZhao-LLMer/A_Dynamic_Multi-Modal_Deep_Reinforcement_Learning_Framework_for_3D_Bin_Packing_Problem)  

# Service
**Reviewer/Program Committee Member:**
ICLR2026, CVPR2026, ECCV2026, ICML2026

**Teaching Assistant:**    
COMP 5311: Internet Infrastructure and Protocols, Fall 2025, PolyU  

<div id="mapmyvisitors-widget" style="width:40%; margin: 0 auto; display:block;">
<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=afTwX2ycX1wEm9gTuX9zoo-NhxMLThqkW2-0vJ83YqU&cl=ffffff&w=a"></script>
</div>
