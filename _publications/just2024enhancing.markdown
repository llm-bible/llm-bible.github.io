---
layout: publication
title: Dipt Enhancing LLM Reasoning Through Diversified Perspective-taking
authors: Just Hoang Anh, Dabas Mahavir, Huang Lifu, Jin Ming, Jia Ruoxi
conference: "Arxiv"
year: 2024
bibkey: just2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06241"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Existing work on improving language model reasoning typically explores a single solution path which can be prone to errors. Inspired by perspective-taking in social studies this paper introduces DiPT a novel approach that complements current reasoning methods by explicitly incorporating diversified viewpoints. This approach allows the model to gain a deeper understanding of the problems context and identify the most effective solution path during the inference stage. Additionally it provides a general data-centric AI recipe for augmenting existing data to improve their quality for fine-tuning. Our empirical results demonstrate that DiPT can be flexibly integrated into existing methods that focus on a single reasoning approach enhancing their reasoning performance and stability when presented with paraphrased problems. Furthermore we illustrate improved context understanding by maintaining the models safe outputs against jailbreaking prompts intentionally designed to bypass safeguards built into deployed models. Lastly we show that fine-tuning with data enriched with diverse perspectives can boost the reasoning capabilities of the model compared to fine-tuning with raw data alone.
