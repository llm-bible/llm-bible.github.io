---
layout: publication
title: 'Patch-level Training For Large Language Models'
authors: Shao Chenze, Meng Fandong, Zhou Jie
conference: "Arxiv"
year: 2024
bibkey: shao2024patch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12665"}
  - {name: "Code", url: "https://github.com/shaochenze/PatchTrain"}
tags: ['Efficiency And Optimization', 'Has Code', 'Reinforcement Learning', 'Training Techniques', 'Uncategorized']
---
As Large Language Models (LLMs) achieve remarkable progress in language understanding and generation, their training efficiency has become a critical concern. Traditionally, LLMs are trained to predict the next token in a sequence. Despite the success of token-level training, it suffers from considerable computational costs due to the need to process an extensive number of tokens. To mitigate this issue, this paper introduces patch-level training for LLMs, which reduces the sequence length by compressing multiple tokens into a single patch. During patch-level training, we feed the language model shorter sequences of patches and train it to predict the next patch, thereby processing the majority of the training data at a significantly reduced computational cost. Following this, the model continues token-level training on the remaining training data to align with the inference mode. Experiments on a diverse range of models (370M-2.7B parameters) demonstrate that patch-level training can reduce overall computational costs to 0.5\\(\times\\), without compromising the model performance compared to token-level training. Source code: \url\{https://github.com/shaochenze/PatchTrain\}.
