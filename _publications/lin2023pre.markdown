---
layout: publication
title: VILA On Pre45;training For Visual Language Models
authors: Lin Ji, Yin Hongxu, Ping Wei, Lu Yao, Molchanov Pavlo, Tao Andrew, Mao Huizi, Kautz Jan, Shoeybi Mohammad, Han Song
conference: "Arxiv"
year: 2023
bibkey: lin2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.07533"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Visual language models (VLMs) rapidly progressed with the recent success of large language models. There have been growing efforts on visual instruction tuning to extend the LLM with visual inputs but lacks an in45;depth study of the visual language pre45;training process where the model learns to perform joint modeling on both modalities. In this work we examine the design options for VLM pre45;training by augmenting LLM towards VLM through step45;by45;step controllable comparisons. We introduce three main findings (1) freezing LLMs during pre45;training can achieve decent zero45;shot performance but lack in45;context learning capability which requires unfreezing the LLM; (2) interleaved pre45;training data is beneficial whereas image45;text pairs alone are not optimal; (3) re45;blending text45;only instruction data to image45;text data during instruction fine45;tuning not only remedies the degradation of text45;only tasks but also boosts VLM task accuracy. With an enhanced pre45;training recipe we build VILA a Visual Language model family that consistently outperforms the state45;of45;the45;art models e.g. LLaVA45;1.5 across main benchmarks without bells and whistles. Multi45;modal pre45;training also helps unveil appealing properties of VILA including multi45;image reasoning enhanced in45;context learning and better world knowledge.
