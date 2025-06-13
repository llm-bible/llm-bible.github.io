---
layout: publication
title: 'Comfymind: Toward General-purpose Generation Via Tree-based Planning And Reactive Feedback'
authors: Litao Hkust Guo, Xinli Hkust Xu, Luozhou Hkust Wang, Jiantao Hkust Lin, Jinsong Hkust Zhou, Zixin Hkust Zhang, Bolan Bytedance Su, Ying-cong 1 And 2 Chen
conference: "Arxiv"
year: 2025
bibkey: guo2025toward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17908'}
  - {name: "Code", url: 'https://github.com/LitaoGuo/ComfyMind'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'GPT', 'Reinforcement Learning']
---
With the rapid advancement of generative models, general-purpose generation has gained increasing attention as a promising approach to unify diverse tasks across modalities within a single system. Despite this progress, existing open-source frameworks often remain fragile and struggle to support complex real-world applications due to the lack of structured workflow planning and execution-level feedback. To address these limitations, we present ComfyMind, a collaborative AI system designed to enable robust and scalable general-purpose generation, built on the ComfyUI platform. ComfyMind introduces two core innovations: Semantic Workflow Interface (SWI) that abstracts low-level node graphs into callable functional modules described in natural language, enabling high-level composition and reducing structural errors; Search Tree Planning mechanism with localized feedback execution, which models generation as a hierarchical decision process and allows adaptive correction at each stage. Together, these components improve the stability and flexibility of complex generative workflows. We evaluate ComfyMind on three public benchmarks: ComfyBench, GenEval, and Reason-Edit, which span generation, editing, and reasoning tasks. Results show that ComfyMind consistently outperforms existing open-source baselines and achieves performance comparable to GPT-Image-1. ComfyMind paves a promising path for the development of open-source general-purpose generative AI systems. Project page: https://github.com/LitaoGuo/ComfyMind
