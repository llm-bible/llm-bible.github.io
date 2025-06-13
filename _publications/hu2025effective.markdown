---
layout: publication
title: 'GRIFFIN: Effective Token Alignment For Faster Speculative Decoding'
authors: Shijing Hu, Jingyang Li, Xingyu Xie, Zhihui Lu, Kim-chuan Toh, Pan Zhou
conference: "Arxiv"
year: 2025
bibkey: hu2025effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11018"}
  - {name: "Code", url: "https://github.com/hsj576/GRIFFIN"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Training Techniques', 'Has Code']
---
Speculative decoding accelerates inference in large language models (LLMs) by generating multiple draft tokens simultaneously. However, existing methods often struggle with token misalignment between the training and decoding phases, limiting their performance. To address this, we propose GRIFFIN, a novel framework that incorporates a token-alignable training strategy and a token-alignable draft model to mitigate misalignment. The training strategy employs a loss masking mechanism to exclude highly misaligned tokens during training, preventing them from negatively impacting the draft model's optimization. The token-alignable draft model introduces input tokens to correct inconsistencies in generated features. Experiments on LLaMA, Vicuna, Qwen and Mixtral models demonstrate that GRIFFIN achieves an average acceptance length improvement of over 8% and a speedup ratio exceeding 7%, outperforming current speculative decoding state-of-the-art methods. Our code and GRIFFIN's draft models are released publicly in https://github.com/hsj576/GRIFFIN.
