---
layout: publication
title: 'Scaling In-context Demonstrations With Structured Attention'
authors: Cai Tianle, Huang Kaixuan, Lee Jason D., Wang Mengdi
conference: "Arxiv"
year: 2023
bibkey: cai2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.02690"}
tags: ['Attention Mechanism', 'In Context Learning', 'Merging', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
The recent surge of large language models (LLMs) highlights their ability to
perform in-context learning, i.e., "learning" to perform a task from a few
demonstrations in the context without any parameter updates. However, their
capabilities of in-context learning are limited by the model architecture: 1)
the use of demonstrations is constrained by a maximum sentence length due to
positional embeddings; 2) the quadratic complexity of attention hinders users
from using more demonstrations efficiently; 3) LLMs are shown to be sensitive
to the order of the demonstrations. In this work, we tackle these challenges by
proposing a better architectural design for in-context learning. We propose
SAICL (Structured Attention for In-Context Learning), which replaces the
full-attention by a structured attention mechanism designed for in-context
learning, and removes unnecessary dependencies between individual
demonstrations, while making the model invariant to the permutation of
demonstrations. We evaluate SAICL in a meta-training framework and show that
SAICL achieves comparable or better performance than full attention while
obtaining up to 3.4x inference speed-up. SAICL also consistently outperforms a
strong Fusion-in-Decoder (FiD) baseline which processes each demonstration
independently. Finally, thanks to its linear nature, we demonstrate that SAICL
can easily scale to hundreds of demonstrations with continuous performance
gains with scaling.
