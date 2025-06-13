---
layout: publication
title: 'Safesteer: Interpretable Safety Steering With Refusal-evasion In Llms'
authors: Shaona Ghosh, Amrita Bhattacharjee, Yftah Ziser, Christopher Parisien
conference: "Arxiv"
year: 2025
bibkey: ghosh2025interpretable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.04250'}
tags: ['Interpretability and Explainability', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) to adapt to evolving safety policies is costly and impractical. Mechanistic interpretability enables inference-time control through latent activation steering, yet its potential for precise, customizable safety adjustments remains largely untapped. This paper investigates an approach called SafeSteer for guiding the outputs of LLMs by: (i) leveraging category-specific steering vectors for more precise control, (ii) employing a simple, gradient-free unsupervised method to enhance safety steering while preserving text quality, topic relevance, and without explicit refusal, and (iii) accomplishing this without a hard requirement of contrastive pairwise safe data. We also highlight that our method, being simple and effective, aligns with recent studies suggesting that simple techniques often outperform more complex ones in activation steering. We showcase the effectiveness of our approach across various LLMs, datasets, and risk categories, demonstrating its ability to provide precise control, prevent blanket refusals, and guide models toward generating safe content while maintaining topic relevance.
