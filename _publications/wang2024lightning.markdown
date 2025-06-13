---
layout: publication
title: 'In-context Former: Lightning-fast Compressing Context For Large Language Model'
authors: Xiangfeng Wang, Zaiyi Chen, Zheyong Xie, Tong Xu, Yongyi He, Enhong Chen
conference: "Arxiv"
year: 2024
bibkey: wang2024lightning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13618"}
tags: ['Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
With the rising popularity of Transformer-based large language models (LLMs),
reducing their high inference costs has become a significant research focus.
One effective approach is to compress the long input contexts. Existing methods
typically leverage the self-attention mechanism of the LLM itself for context
compression. While these methods have achieved notable results, the compression
process still involves quadratic time complexity, which limits their
applicability. To mitigate this limitation, we propose the In-Context Former
(IC-Former). Unlike previous methods, IC-Former does not depend on the target
LLMs. Instead, it leverages the cross-attention mechanism and a small number of
learnable digest tokens to directly condense information from the contextual
word embeddings. This approach significantly reduces inference time, which
achieves linear growth in time complexity within the compression range.
Experimental results indicate that our method requires only 1/32 of the
floating-point operations of the baseline during compression and improves
processing speed by 68 to 112 times while achieving over 90% of the baseline
performance on evaluation metrics. Overall, our model effectively reduces
compression costs and makes real-time compression scenarios feasible.
