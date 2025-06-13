---
layout: publication
title: 'Align Attention Heads Before Merging Them: An Effective Way For Converting MHA To GQA'
authors: Qingyun Jin, Xiaohui Song, Feng Zhou, Zengchang Qin
conference: "Arxiv"
year: 2024
bibkey: jin2024align
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20677"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Merging', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
Large language models have been shown to perform well on a variety of natural
language processing problems. However, as the model size and the input
sequence's length increase, the rapid increase of KV Cache significantly slows
down inference speed. Therefore GQA model, as an alternative to MHA model, has
been widely introduced into LLMs. In this work, we propose a low-cost method
for pruning MHA models into GQA models with any compression ratio of key-value
heads. Our method is based on \\(\mathit\{L_0\}\\) masks to gradually remove
redundant parameters. In addition, we apply orthogonal transformations to
attention heads without changing the model to increase similarity between
attention heads before pruning training, in order to further improve
performance of the model. Our method can be compatible with rotary position
embedding (RoPE), which means the model after training can be fully adapted to
the mainstream standard GQA framework. Experiments demonstrate that our
strategy can compress up to 87.5% of key-value heads of the LLaMA2-7B model
without too much performance degradation, just achieved through supervised
fine-tuning.
