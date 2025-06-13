---
layout: publication
title: 'COSMOS: Predictable And Cost-effective Adaptation Of Llms'
authors: Jiayu Wang, Aws Albarghouthi, Frederic Sala
conference: "Arxiv"
year: 2025
bibkey: wang2025predictable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01449"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Scaling Laws', 'RAG', 'Pretraining Methods', 'Large-Scale Training', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'In-Context Learning']
---
Large language models (LLMs) achieve remarkable performance across numerous tasks by using a diverse array of adaptation strategies. However, optimally selecting a model and adaptation strategy under resource constraints is challenging and often requires extensive experimentation. We investigate whether it is possible to accurately predict both performance and cost without expensive trials. We formalize the strategy selection problem for LLMs and introduce COSMOS, a unified prediction framework that efficiently estimates adaptation outcomes at minimal cost. We instantiate and study the capability of our framework via a pair of powerful predictors: embedding-augmented lightweight proxy models to predict fine-tuning performance, and low-sample scaling laws to forecast retrieval-augmented in-context learning. Extensive evaluation across eight representative benchmarks demonstrates that COSMOS achieves high prediction accuracy while reducing computational costs by 92.72% on average, and up to 98.71% in resource-intensive scenarios. Our results show that efficient prediction of adaptation outcomes is not only feasible but can substantially reduce the computational overhead of LLM deployment while maintaining performance standards.
