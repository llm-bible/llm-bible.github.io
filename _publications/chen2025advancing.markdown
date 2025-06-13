---
layout: publication
title: 'Decisionflow: Advancing Large Language Model As Principled Decision Maker'
authors: Xiusi Chen, Shanyong Wang, Cheng Qian, Hongru Wang, Peixuan Han, Heng Ji
conference: "Arxiv"
year: 2025
bibkey: chen2025advancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21397'}
  - {name: "Code", url: 'https://github.com/xiusic/DecisionFlow'}
tags: ['Reinforcement Learning', 'Prompting', 'Has Code', 'Tools']
---
In high-stakes domains such as healthcare and finance, effective decision-making demands not just accurate outcomes but transparent and explainable reasoning. However, current language models often lack the structured deliberation needed for such tasks, instead generating decisions and justifications in a disconnected, post-hoc manner. To address this, we propose DecisionFlow, a novel decision modeling framework that guides models to reason over structured representations of actions, attributes, and constraints. Rather than predicting answers directly from prompts, DecisionFlow builds a semantically grounded decision space and infers a latent utility function to evaluate trade-offs in a transparent, utility-driven manner. This process produces decisions tightly coupled with interpretable rationales reflecting the model's reasoning. Empirical results on two high-stakes benchmarks show that DecisionFlow not only achieves up to 30% accuracy gains over strong prompting baselines but also enhances alignment in outcomes. Our work is a critical step toward integrating symbolic reasoning with LLMs, enabling more accountable, explainable, and reliable LLM decision support systems. We release the data and code at https://github.com/xiusic/DecisionFlow.
