---
layout: publication
title: 'Rethinking Predictive Modeling For LLM Routing: When Simple Knn Beats Complex Learned Routers'
authors: Yang Li
conference: "Arxiv"
year: 2025
bibkey: li2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12601"}
tags: ['Reinforcement Learning', 'Training Techniques', 'Fine-Tuning', 'Model Architecture']
---
As large language models (LLMs) grow in scale and specialization, routing--selecting the best model for a given input--has become essential for efficient and effective deployment. While recent methods rely on complex learned routing strategies, their dependence on disparate training data and evaluation setups makes comparison and generalization difficult. In this work, we revisit LLM routing through the lens of simplicity. We show that a well-tuned k-Nearest Neighbors (kNN) approach not only matches but often outperforms state-of-the-art learned routers across diverse tasks. To support systematic evaluation, we introduce a suite of standardized routing benchmarks spanning instruction-following, question-answering, and reasoning tasks, as well as the first multi-modal routing dataset involving visual inputs. Our findings reveal that the locality properties of model performance in embedding space enable simple non-parametric methods to achieve strong routing decisions with lower sample complexity than parametric approaches. This challenges the prevailing trend toward sophisticated architectures and highlights the importance of thoroughly evaluating simple baselines before investing in complex solutions. To support reproducibility and further exploration, we will release all benchmarks and code upon publication.
