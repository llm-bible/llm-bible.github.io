---
layout: publication
title: A Theory Of Emergent In-context Learning As Implicit Structure Induction
authors: Hahn Michael, Goyal Navin
conference: "Arxiv"
year: 2023
bibkey: hahn2023theory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.07971"}
tags: ['In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Scaling large language models (LLMs) leads to an emergent capacity to learn in-context from example demonstrations. Despite progress theoretical understanding of this phenomenon remains limited. We argue that in-context learning relies on recombination of compositional operations found in natural language data. We derive an information-theoretic bound showing how in-context learning abilities arise from generic next-token prediction when the pretraining distribution has sufficient amounts of compositional structure under linguistically motivated assumptions. A second bound provides a theoretical justification for the empirical success of prompting LLMs to output intermediate steps towards an answer. To validate theoretical predictions we introduce a controlled setup for inducing in-context learning; unlike previous approaches it accounts for the compositional nature of language. Trained transformers can perform in-context learning for a range of tasks in a manner consistent with the theoretical results. Mirroring real-world LLMs in a miniature setup in-context learning emerges when scaling parameters and data and models perform better when prompted to output intermediate steps. Probing shows that in-context learning is supported by a representation of the inputs compositional structure. Taken together these results provide a step towards theoretical understanding of emergent behavior in large language models.
