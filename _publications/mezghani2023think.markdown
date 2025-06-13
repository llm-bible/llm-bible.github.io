---
layout: publication
title: 'Think Before You Act: Unified Policy For Interleaving Language Reasoning With Actions'
authors: Lina Mezghani, Piotr Bojanowski, Karteek Alahari, Sainbayar Sukhbaatar
conference: "Reincarnating Reinforcement Learning Workshop at ICLR 2023"
year: 2023
bibkey: mezghani2023think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.11063"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Transformer']
---
The success of transformer models trained with a language modeling objective
brings a promising opportunity to the reinforcement learning framework.
Decision Transformer is a step towards this direction, showing how to train
transformers with a similar next-step prediction objective on offline data.
Another important development in this area is the recent emergence of
large-scale datasets collected from the internet, such as the ones composed of
tutorial videos with captions where people talk about what they are doing. To
take advantage of this language component, we propose a novel method for
unifying language reasoning with actions in a single policy. Specifically, we
augment a transformer policy with word outputs, so it can generate textual
captions interleaved with actions. When tested on the most challenging task in
BabyAI, with captions describing next subgoals, our reasoning policy
consistently outperforms the caption-free baseline.
