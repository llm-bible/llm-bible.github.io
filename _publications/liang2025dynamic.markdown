---
layout: publication
title: 'Dynamic Token Reduction During Generation For Vision Language Models'
authors: Xiaoyu Liang, Chaofeng Guan, Jiaying Lu, Huiyao Chen, Huan Wang, Haoji Hu
conference: "Arxiv"
year: 2025
bibkey: liang2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14204"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Pruning', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Vision-Language Models (VLMs) have achieved notable success in multimodal
tasks but face practical limitations due to the quadratic complexity of decoder
attention mechanisms and autoregressive generation. Existing methods like FASTV
and VTW have achieved notable results in reducing redundant visual tokens, but
these approaches focus on pruning tokens in a single forward pass without
systematically analyzing the redundancy of visual tokens throughout the entire
generation process. In this paper, we introduce a dynamic pruning strategy
tailored for VLMs, namedDynamic Rate (DyRate), which progressively adjusts the
compression rate during generation. Our analysis of the distribution of
attention reveals that the importance of visual tokens decreases throughout the
generation process, inspiring us to adopt a more aggressive compression rate.
By integrating a lightweight predictor based on attention distribution, our
approach enables flexible adjustment of pruning rates based on the attention
distribution. Our experimental results demonstrate that our method not only
reduces computational demands but also maintains the quality of responses.
