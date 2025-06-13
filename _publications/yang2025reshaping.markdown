---
layout: publication
title: 'Reshaping Representation Space To Balance The Safety And Over-rejection In Large Audio Language Models'
authors: Hao Yang, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari
conference: "Arxiv"
year: 2025
bibkey: yang2025reshaping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19670"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Large Audio Language Models (LALMs) have extended the capabilities of Large Language Models (LLMs) by enabling audio-based human interactions. However, recent research has revealed that LALMs remain vulnerable to harmful queries due to insufficient safety-alignment. Despite advances in defence measures for text and vision LLMs, effective safety-alignment strategies and audio-safety dataset specifically targeting LALMs are notably absent. Meanwhile defence measures based on Supervised Fine-tuning (SFT) struggle to address safety improvement while avoiding over-rejection issues, significantly compromising helpfulness. In this work, we propose an unsupervised safety-fine-tuning strategy as remedy that reshapes model's representation space to enhance existing LALMs safety-alignment while balancing the risk of over-rejection. Our experiments, conducted across three generations of Qwen LALMs, demonstrate that our approach significantly improves LALMs safety under three modality input conditions (audio-text, text-only, and audio-only) while increasing over-rejection rate by only 0.88% on average. Warning: this paper contains harmful examples.
