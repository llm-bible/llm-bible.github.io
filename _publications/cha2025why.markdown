---
layout: publication
title: 'Why Knowledge Distillation Works In Generative Models: A Minimal Working Explanation'
authors: Sungmin Cha, Kyunghyun Cho
conference: "Arxiv"
year: 2025
bibkey: cha2025why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13111"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Distillation', 'Interpretability and Explainability']
---
Knowledge distillation (KD) is a core component in the training and deployment of modern generative models, particularly large language models (LLMs). While its empirical benefits are well documented--enabling smaller student models to emulate the performance of much larger teachers--the underlying mechanisms by which KD improves generative quality remain poorly understood. In this work, we present a minimal working explanation of KD in generative modeling. Using a controlled simulation with mixtures of Gaussians, we demonstrate that distillation induces a trade-off between precision and recall in the student model. As the teacher distribution becomes more selective, the student concentrates more probability mass on high-likelihood regions at the expense of coverage--a behavior modulated by a single entropy-controlling parameter. We then validate this effect in a large-scale language modeling setup using the SmolLM2 family of models. Empirical results reveal the same precision-recall dynamics observed in simulation, where precision corresponds to sample quality and recall to distributional coverage. This precision-recall trade-off proves especially beneficial in scenarios where sample quality outweighs diversity, such as instruction tuning or downstream generation. Our analysis provides a simple and general explanation for the effectiveness of KD in generative modeling.
