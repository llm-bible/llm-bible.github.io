---
layout: publication
title: 'Uncertainty-aware Unlikelihood Learning Improves Generative Aspect Sentiment Quad Prediction'
authors: Hu Mengting, Bai Yinhao, Wu Yike, Zhang Zhen, Zhang Liqi, Gao Hang, Zhao Shiwan, Huang Minlie
conference: "Arxiv"
year: 2023
bibkey: hu2023uncertainty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00418"}
tags: ['Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Uncategorized']
---
Recently, aspect sentiment quad prediction has received widespread attention in the field of aspect-based sentiment analysis. Existing studies extract quadruplets via pre-trained generative language models to paraphrase the original sentence into a templated target sequence. However, previous works only focus on what to generate but ignore what not to generate. We argue that considering the negative samples also leads to potential benefits. In this work, we propose a template-agnostic method to control the token-level generation, which boosts original learning and reduces mistakes simultaneously. Specifically, we introduce Monte Carlo dropout to understand the built-in uncertainty of pre-trained language models, acquiring the noises and errors. We further propose marginalized unlikelihood learning to suppress the uncertainty-aware mistake tokens. Finally, we introduce minimization entropy to balance the effects of marginalized unlikelihood learning. Extensive experiments on four public datasets demonstrate the effectiveness of our approach on various generation templates.
