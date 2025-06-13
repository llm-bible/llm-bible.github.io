---
layout: publication
title: 'Mme5: Improving Multimodal Multilingual Embeddings Via High-quality Synthetic Data'
authors: Haonan Chen, Liang Wang, Nan Yang, Yutao Zhu, Ziliang Zhao, Furu Wei, Zhicheng Dou
conference: "Arxiv"
year: 2025
bibkey: chen2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08468'}
  - {name: "Code", url: 'https://github.com/haon-chen/mmE5'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal embedding models have gained significant attention for their
ability to map data from different modalities, such as text and images, into a
unified representation space. However, the limited labeled multimodal data
often hinders embedding performance. Recent approaches have leveraged data
synthesis to address this problem, yet the quality of synthetic data remains a
critical bottleneck. In this work, we identify three criteria for high-quality
synthetic multimodal data. First, broad scope ensures that the generated data
covers diverse tasks and modalities, making it applicable to various downstream
scenarios. Second, robust cross-modal alignment makes different modalities
semantically consistent. Third, high fidelity ensures that the synthetic data
maintains realistic details to enhance its reliability. Guided by these
principles, we synthesize datasets that: (1) cover a wide range of tasks,
modality combinations, and languages, (2) are generated via a deep thinking
process within a single pass of a multimodal large language model, and (3)
incorporate real-world images with accurate and relevant texts, ensuring
fidelity through self-evaluation and refinement. Leveraging these high-quality
synthetic and labeled datasets, we train a multimodal multilingual E5 model
mmE5. Extensive experiments demonstrate that mmE5 achieves state-of-the-art
performance on the MMEB Benchmark and superior multilingual performance on the
XTD benchmark. Our codes, datasets and models are released in
https://github.com/haon-chen/mmE5.
