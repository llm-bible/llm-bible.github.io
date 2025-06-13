---
layout: publication
title: 'ALN-P3: Unified Language Alignment For Perception, Prediction, And Planning In Autonomous Driving'
authors: Yunsheng Ma, Burhaneddin Yaman, Xin Ye, Mahmut Yurt, Jingru Luo, Abhirup Mallik, Ziran Wang, Liu Ren
conference: "Arxiv"
year: 2025
bibkey: ma2025aln
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15158'}
tags: ['Interpretability and Explainability', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools', 'Multimodal Models']
---
Recent advances have explored integrating large language models (LLMs) into end-to-end autonomous driving systems to enhance generalization and interpretability. However, most existing approaches are limited to either driving performance or vision-language reasoning, making it difficult to achieve both simultaneously. In this paper, we propose ALN-P3, a unified co-distillation framework that introduces cross-modal alignment between "fast" vision-based autonomous driving systems and "slow" language-driven reasoning modules. ALN-P3 incorporates three novel alignment mechanisms: Perception Alignment (P1A), Prediction Alignment (P2A), and Planning Alignment (P3A), which explicitly align visual tokens with corresponding linguistic outputs across the full perception, prediction, and planning stack. All alignment modules are applied only during training and incur no additional costs during inference. Extensive experiments on four challenging benchmarks-nuScenes, Nu-X, TOD3Cap, and nuScenes QA-demonstrate that ALN-P3 significantly improves both driving decisions and language reasoning, achieving state-of-the-art results.
