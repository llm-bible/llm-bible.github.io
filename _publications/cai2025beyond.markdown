---
layout: publication
title: 'Beyond Demonstrations: Dynamic Vector Construction From Latent Representations'
authors: Wang Cai, Hsiu-yuan Huang, Zhixiang Wang, Yunfang Wu
conference: "Arxiv"
year: 2025
bibkey: cai2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20318"}
tags: ['Efficiency and Optimization', 'Few-Shot', 'RAG', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
In-Context derived Vector (ICV) methods extract task-relevant representations from large language models (LLMs) and reinject them during inference, achieving comparable performance to few-shot In-Context Learning (ICL) without repeated demonstration processing. However, existing ICV methods remain sensitive to ICL-specific factors, often use coarse or semantically fragmented representations as the source of the vector, and rely on heuristic-based injection positions, limiting their applicability.
  To address these issues, we propose Dynamic Vector (DyVec), which incorporates an Exhaustive Query Rotation (EQR) strategy to extract robust semantically aggregated latent representations by mitigating variance introduced by ICL. It then applies Dynamic Latent Segmentation and Injection to adaptively partition representations based on task complexity and leverages REINFORCE-based optimization to learn optimal injection positions for each segment.
  Experiments results show that DyVec outperforms few-shot ICL, LoRA, and prior ICV baselines. Further analysis highlights the effectiveness of dynamically segmenting and injecting semantically aggregated latent representations. DyVec provides a lightweight and data-efficient solution for inference-time task adaptation.
