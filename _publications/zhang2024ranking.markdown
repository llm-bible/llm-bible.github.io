---
layout: publication
title: 'Rankclip: Ranking-consistent Language-image Pretraining'
authors: Yiming Zhang, Zhuokai Zhao, Zhaorun Chen, Zhili Feng, Zenghui Ding, Yining Sun
conference: "Arxiv"
year: 2024
bibkey: zhang2024ranking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09387"}
tags: ['Pre-Training', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Self-supervised contrastive learning models, such as CLIP, have set new
benchmarks for vision-language models in many downstream tasks. However, their
dependency on rigid one-to-one mappings overlooks the complex and often
multifaceted relationships between and within texts and images. To this end, we
introduce RankCLIP, a novel pre-training method that extends beyond the rigid
one-to-one matching framework of CLIP and its variants. By extending the
traditional pair-wise loss to list-wise, and leveraging both in-modal and
cross-modal ranking consistency, RankCLIP improves the alignment process,
enabling it to capture the nuanced many-to-many relationships between and
within each modality. Through comprehensive experiments, we demonstrate the
effectiveness of RankCLIP in various downstream tasks, notably achieving
significant gains in zero-shot classifications over state-of-the-art methods,
underscoring the importance of this enhanced learning process.
