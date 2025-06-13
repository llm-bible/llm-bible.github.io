---
layout: publication
title: 'Reneg: Learning Negative Embedding With Reward Guidance'
authors: Xiaomin Li, Yixuan Liu, Takashi Isobe, Xu Jia, Qinpeng Cui, Dong Zhou, Dong Li, You He, Huchuan Lu, Zhongdao Wang, Emad Barsoum
conference: "Arxiv"
year: 2024
bibkey: li2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.19637"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Prompting', 'Applications']
---
In text-to-image (T2I) generation applications, negative embeddings have
proven to be a simple yet effective approach for enhancing generation quality.
Typically, these negative embeddings are derived from user-defined negative
prompts, which, while being functional, are not necessarily optimal. In this
paper, we introduce ReNeg, an end-to-end method designed to learn improved
Negative embeddings guided by a Reward model. We employ a reward feedback
learning framework and integrate classifier-free guidance (CFG) into the
training process, which was previously utilized only during inference, thus
enabling the effective learning of negative embeddings. We also propose two
strategies for learning both global and per-sample negative embeddings.
Extensive experiments show that the learned negative embedding significantly
outperforms null-text and handcrafted counterparts, achieving substantial
improvements in human preference alignment. Additionally, the negative
embedding learned within the same text embedding space exhibits strong
generalization capabilities. For example, using the same CLIP text encoder, the
negative embedding learned on SD1.5 can be seamlessly transferred to
text-to-image or even text-to-video models such as ControlNet, ZeroScope, and
VideoCrafter2, resulting in consistent performance improvements across the
board.
