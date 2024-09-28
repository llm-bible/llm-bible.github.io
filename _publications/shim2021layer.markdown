---
layout: publication
title: Layer-wise Pruning of Transformer Attention Heads for Efficient Language Modeling
authors: Shim Kyuhong, Choi Iksoo, Sung Wonyong, Choi Jungwook
conference: "Arxiv"
year: 2021
bibkey: shim2021layer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.03252"}
tags: ['ARXIV', 'Language Modeling', 'Model Architecture', 'Pruning', 'Transformer']
---
While Transformer-based models have shown impressive language modeling performance the large computation cost is often prohibitive for practical use. Attention head pruning which removes unnecessary attention heads in the multihead attention is a promising technique to solve this problem. However it does not evenly reduce the overall load because the heavy feedforward module is not affected by head pruning. In this paper we apply layer-wise attention head pruning on All-attention Transformer so that the entire computation and the number of parameters can be reduced proportionally to the number of pruned heads. While the architecture has the potential to fully utilize head pruning we propose three training methods that are especially helpful to minimize performance degradation and stabilize the pruning process. Our pruned model shows consistently lower perplexity within a comparable parameter size than Transformer-XL on WikiText-103 language modeling benchmark.
