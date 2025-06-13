---
layout: publication
title: 'Trace-of-thought Prompting: Investigating Prompt-based Knowledge Distillation Through Question Decomposition'
authors: Tyler Mcdonald, Ali Emami
conference: "Arxiv"
year: 2025
bibkey: mcdonald2025trace
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20946"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting']
---
Knowledge distillation allows smaller neural networks to emulate the
performance of larger, teacher models with reduced computational demands.
Traditional methods for Large Language Models (LLMs) often necessitate
extensive fine-tuning, which limits their accessibility. To address this, we
introduce Trace-of-Thought Prompting, a novel framework designed to distill
critical reasoning capabilities from high-resource teacher models (over 8
billion parameters) to low-resource student models (up to 8 billion
parameters). This approach leverages problem decomposition to enhance
interpretability and facilitate human-in-the-loop interventions. Empirical
evaluations on the GSM8K and MATH datasets show that student models achieve
accuracy gains of up to 113% on GSM8K and 21% on MATH, with significant
improvements particularly notable in smaller models like Llama 2 and Zephyr.
Our results suggest a promising pathway for open-source, low-resource models to
eventually serve both as both students and teachers, potentially reducing our
reliance on high-resource, proprietary models.
