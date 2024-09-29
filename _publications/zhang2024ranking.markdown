---
layout: publication
title: Rankclip\: Ranking-consistent Language-image Pretraining
authors: Zhang Yiming, Zhao Zhuokai, Chen Zhaorun, Feng Zhili, Ding Zenghui, Sun Yining
conference: "Arxiv"
year: 2024
bibkey: zhang2024ranking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09387"}
tags: ['Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Self-supervised contrastive learning models such as CLIP have set new benchmarks for vision-language models in many downstream tasks. However their dependency on rigid one-to-one mappings overlooks the complex and often multifaceted relationships between and within texts and images. To this end we introduce RANKCLIP a novel pretraining method that extends beyond the rigid one-to-one matching framework of CLIP and its variants. By extending the traditional pair-wise loss to list-wise and leveraging both in-modal and cross-modal ranking consistency RANKCLIP improves the alignment process enabling it to capture the nuanced many-to-many relationships between and within each modality. Through comprehensive experiments we demonstrate the effectiveness of RANKCLIP in various downstream tasks notably achieving significant gains in zero-shot classifications over state-of-the-art methods underscoring the importance of this enhanced learning process.
