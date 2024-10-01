---
layout: publication
title: 'Robust Dialogue State Tracking With Weak Supervision And Sparse Data'
authors: Heck Michael, Lubis Nurul, Van Niekerk Carel, Feng Shutong, Geishauser Christian, Lin Hsien-chin, Gašić Milica
conference: "Arxiv"
year: 2022
bibkey: heck2022robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.03354"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Transformer']
---
Generalising dialogue state tracking (DST) to new data is especially challenging due to the strong reliance on abundant and fine-grained supervision during training. Sample sparsity, distributional shift and the occurrence of new concepts and topics frequently lead to severe performance degradation during inference. In this paper we propose a training strategy to build extractive DST models without the need for fine-grained manual span labels. Two novel input-level dropout methods mitigate the negative impact of sample sparsity. We propose a new model architecture with a unified encoder that supports value as well as slot independence by leveraging the attention mechanism. We combine the strengths of triple copy strategy DST and value matching to benefit from complementary predictions without violating the principle of ontology independence. Our experiments demonstrate that an extractive DST model can be trained without manual span labels. Our architecture and training strategies improve robustness towards sample sparsity, new concepts and topics, leading to state-of-the-art performance on a range of benchmarks. We further highlight our model's ability to effectively learn from non-dialogue data.
