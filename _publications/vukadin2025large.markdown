---
layout: publication
title: 'Large Language Models As Attribution Regularizers For Efficient Model Training'
authors: Davor Vukadin, Marin Šilić, Goran Delač
conference: "Arxiv"
year: 2025
bibkey: vukadin2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20268"}
tags: ['Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Few-Shot']
---
Large Language Models (LLMs) have demonstrated remarkable performance across
diverse domains. However, effectively leveraging their vast knowledge for
training smaller downstream models remains an open challenge, especially in
domains like tabular data learning, where simpler models are often preferred
due to interpretability and efficiency.
  In this paper, we introduce a novel yet straightforward method for
incorporating LLM-generated global task feature attributions into the training
process of smaller networks. Specifically, we propose an attribution-matching
regularization term that aligns the training dynamics of the smaller model with
the insights provided by the LLM. By doing so, our approach yields superior
performance in few-shot learning scenarios. Notably, our method requires only
black-box API access to the LLM, making it easy to integrate into existing
training pipelines with minimal computational overhead.
  Furthermore, we demonstrate how this method can be used to address common
issues in real-world datasets, such as skewness and bias. By integrating
high-level knowledge from LLMs, our approach improves generalization, even when
training data is limited or imbalanced. We validate its effectiveness through
extensive experiments across multiple tasks, demonstrating improved learning
efficiency and model robustness.
