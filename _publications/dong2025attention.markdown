---
layout: publication
title: 'Attention Retrieves, MLP Memorizes: Disentangling Trainable Components In The Transformer'
authors: Yihe Dong, Lorenzo Noci, Mikhail Khodak, Mufan Li
conference: "Arxiv"
year: 2025
bibkey: dong2025attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01115"}
tags: ['Training Techniques', 'Model Architecture', 'Language Modeling', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
The Transformer architecture is central to the success of modern Large Language Models (LLMs), in part due to its surprising ability to perform a wide range of algorithmic tasks -- including mathematical reasoning, memorization, and retrieval -- using only gradient-based training on next-token prediction. While the core component of a Transformer is the self-attention mechanism, we question how much, and which aspects, of the performance gains can be attributed to it. To this end, we compare standard Transformers to variants in which either the multi-layer perceptron (MLP) layers or the attention projectors (queries and keys) are frozen at initialization. To further isolate the contribution of attention, we introduce MixiT -- the Mixing Transformer -- a simplified, principled model in which the attention coefficients are entirely random and fixed at initialization, eliminating any input-dependent computation or learning in attention. Surprisingly, we find that MixiT matches the performance of fully trained Transformers on various algorithmic tasks, especially those involving basic arithmetic or focusing heavily on memorization. For retrieval-based tasks, we observe that having input-dependent attention coefficients is consistently beneficial, while MixiT underperforms. We attribute this failure to its inability to form specialized circuits such as induction heads -- a specific circuit known to be crucial for learning and exploiting repeating patterns in input sequences. Even more interestingly, we find that attention with frozen key and query projectors is not only able to form induction heads, but can also perform competitively on language modeling. Our results underscore the importance of architectural heterogeneity, where distinct components contribute complementary inductive biases crucial for solving different classes of tasks.
