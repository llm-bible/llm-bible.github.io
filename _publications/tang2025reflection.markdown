---
layout: publication
title: 'Reflection-window Decoding: Text Generation With Selective Refinement'
authors: Zeyu Tang, Zhenhao Chen, Xiangchen Song, Loka Li, Yunlong Deng, Yifan Shen, Guangyi Chen, Peter Spirtes, Kun Zhang
conference: "Arxiv"
year: 2025
bibkey: tang2025reflection
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.03678'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'GPT', 'Applications', 'Tools', 'Pretraining Methods']
---
The autoregressive decoding for text generation in large language models (LLMs), while widely used, is inherently suboptimal due to the lack of a built-in mechanism to perform refinement and/or correction of the generated content. In this paper, we consider optimality in terms of the joint probability over the generated response, when jointly considering all tokens at the same time. We theoretically characterize the potential deviation of the autoregressively generated response from its globally optimal counterpart that is of the same length. Our analysis suggests that we need to be cautious when noticeable uncertainty arises during text generation, which may signal the sub-optimality of the generation history. To address the pitfall of autoregressive decoding for text generation, we propose an approach that incorporates a sliding reflection window and a pausing criterion, such that refinement and generation can be carried out interchangeably as the decoding proceeds. Our selective refinement framework strikes a balance between efficiency and optimality, and our extensive experimental results demonstrate the effectiveness of our approach.
