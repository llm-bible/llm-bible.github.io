---
layout: publication
title: 'Multi-scale Probabilistic Generation Theory: A Hierarchical Framework For Interpreting Large Language Models'
authors: Yukin Zhang, Qi Dong
conference: "Arxiv"
year: 2025
bibkey: zhang2025multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18244'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Model Architecture', 'BERT', 'Tools', 'GPT', 'Pretraining Methods']
---
Large Transformer based language models achieve remarkable performance but remain opaque in how they plan, structure, and realize text. We introduce Multi_Scale Probabilistic Generation Theory (MSPGT), a hierarchical framework that factorizes generation into three semantic scales_global context, intermediate structure, and local word choices and aligns each scale with specific layer ranges in Transformer architectures. To identify scale boundaries, we propose two complementary metrics: attention span thresholds and inter layer mutual information peaks. Across four representative models (GPT-2, BERT, RoBERTa, and T5), these metrics yield stable local/intermediate/global partitions, corroborated by probing tasks and causal interventions. We find that decoder_only models allocate more layers to intermediate and global processing while encoder_only models emphasize local feature extraction. Through targeted interventions, we demonstrate that local scale manipulations primarily influence lexical diversity, intermediate-scale modifications affect sentence structure and length, and global_scale perturbations impact discourse coherence all with statistically significant effects. MSPGT thus offers a unified, architecture-agnostic method for interpreting, diagnosing, and controlling large language models, bridging the gap between mechanistic interpretability and emergent capabilities.
