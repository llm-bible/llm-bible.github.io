---
layout: publication
title: 'Knowledge-augmented Multimodal Clinical Rationale Generation For Disease Diagnosis With Small Language Models'
authors: Shuai Niu, Jing Ma, Hongzhan Lin, Liang Bai, Zhihua Wang, Yida Xu, Yunya Song, Xian Yang
conference: "Arxiv"
year: 2024
bibkey: niu2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.07611"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'Transformer', 'Interpretability and Explainability', 'Attention Mechanism']
---
Interpretation is critical for disease diagnosis, but existing models
struggle to balance predictive accuracy with human-understandable rationales.
While large language models (LLMs) offer strong reasoning abilities, their
clinical use is limited by high computational costs and restricted multimodal
reasoning ability. Small language models (SLMs) are efficient but lack advanced
reasoning for integrating multimodal medical data. In addition, both LLMs and
SLMs lack of domain knowledge for trustworthy reasoning. Therefore, we propose
ClinRaGen, enhancing SLMs by leveraging LLM-derived reasoning ability via
rationale distillation and domain knowledge injection for trustworthy
multimodal rationale generation. Key innovations include a sequential rationale
distillation framework that equips SLMs with LLM-comparable mutlimodal
reasoning abilities, and a knowledge-augmented attention mechanism that jointly
unifies multimodal representation from time series and textual data in a same
encoding space, enabling it naturally interpreted by SLMs while incorporating
domain knowledge for reliable rationale generation. Experiments on real-world
medical datasets show that ClinRaGen achieves state-of-the-art performance in
disease diagnosis and rationale generation, demonstrating the effectiveness of
combining LLM-driven reasoning with knowledge augmentation for improved
interpretability.
