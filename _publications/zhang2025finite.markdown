---
layout: publication
title: 'Finite State Automata Inside Transformers With Chain-of-thought: A Mechanistic Study On State Tracking'
authors: Yifan Zhang, Wenyu Du, Dongming Jin, Jie Fu, Zhi Jin
conference: "Arxiv"
year: 2025
bibkey: zhang2025finite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20129"}
  - {name: "Code", url: "https://github.com/IvanChangPKU/FSA"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Has Code', 'Pretraining Methods']
---
Chain-of-thought (CoT) significantly enhances the performance of large language models (LLMs) across a wide range of tasks, and prior research shows that CoT can theoretically increase expressiveness. However, there is limited mechanistic understanding of the algorithms that Transformer+CoT can learn. Our key contributions are: (1) We evaluate the state tracking capabilities of Transformer+CoT and its variants, confirming the effectiveness of CoT. (2) Next, we identify the circuit (a subset of model components, responsible for tracking the world state), indicating that late-layer MLP neurons play a key role. We propose two metrics, compression and distinction, and show that the neuron sets for each state achieve nearly 100% accuracy, providing evidence of an implicit finite state automaton (FSA) embedded within the model. (3) Additionally, we explore three challenging settings: skipping intermediate steps, introducing data noises, and testing length generalization. Our results demonstrate that Transformer+CoT learns robust algorithms (FSAs), highlighting its resilience in challenging scenarios. Our code is available at https://github.com/IvanChangPKU/FSA.
