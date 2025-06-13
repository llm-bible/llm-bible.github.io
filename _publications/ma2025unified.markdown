---
layout: publication
title: 'Unitok: A Unified Tokenizer For Visual Generation And Understanding'
authors: Chuofan Ma, Yi Jiang, Junfeng Wu, Jihan Yang, Xin Yu, Zehuan Yuan, Bingyue Peng, Xiaojuan Qi
conference: "Arxiv"
year: 2025
bibkey: ma2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20321"}
  - {name: "Code", url: "https://github.com/FoundationVision/UniTok"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Quantization']
---
Visual generative and understanding models typically rely on distinct tokenizers to process images, presenting a key challenge for unifying them within a single framework. Recent studies attempt to address this by connecting the training of VQVAE (for autoregressive generation) and CLIP (for understanding) to build a unified tokenizer. However, directly combining these training objectives has been observed to cause severe loss conflicts. In this paper, we show that reconstruction and semantic supervision do not inherently conflict. Instead, the underlying bottleneck stems from limited representational capacity of discrete token space. Building on these insights, we introduce UniTok, a unified tokenizer featuring a novel multi-codebook quantization mechanism that effectively scales up the vocabulary size and bottleneck dimension. In terms of final performance, UniTok sets a new record of 0.38 rFID and 78.6% zero-shot accuracy on ImageNet. Besides, UniTok can be seamlessly integrated into MLLMs to unlock native visual generation capability, without compromising the understanding performance. Additionally, we show that UniTok favors cfg-free generation, reducing gFID from 14.6 to 2.5 on ImageNet 256\\(\times\\)256 benchmark. GitHub: https://github.com/FoundationVision/UniTok.
