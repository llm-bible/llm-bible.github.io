---
layout: publication
title: 'Language Models Can Learn Implicit Multi-hop Reasoning, But Only If They Have Lots Of Training Data'
authors: Yuekun Yao, Yupei Du, Dawei Zhu, Michael Hahn, Alexander Koller
conference: "Arxiv"
year: 2025
bibkey: yao2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17923"}
tags: ['Transformer', 'GPT', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Implicit reasoning is the ability of a language model to solve multi-hop reasoning tasks in a single forward pass, without chain of thought. We investigate this capability using GPT2-style language models trained from scratch on controlled \\(k\\)-hop reasoning datasets (\\(k = 2, 3, 4\\)). We show that while such models can indeed learn implicit \\(k\\)-hop reasoning, the required training data grows exponentially in \\(k\\), and the required number of transformer layers grows linearly in \\(k\\). We offer a theoretical explanation for why this depth growth is necessary. We further find that the data requirement can be mitigated, but not eliminated, through curriculum learning.
