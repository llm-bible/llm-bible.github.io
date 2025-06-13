---
layout: publication
title: 'A Contextual-aware Position Encoding For Sequential Recommendation'
authors: Jun Yuan, Guohao Cai, Zhenhua Dong
conference: "Arxiv"
year: 2025
bibkey: yuan2025contextual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09027"}
  - {name: "Code", url: "https://github.com/yjdy/CAPE"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Transformer', 'Has Code', 'Attention Mechanism']
---
Sequential recommendation (SR), which encodes user activity to predict the
next action, has emerged as a widely adopted strategy in developing commercial
personalized recommendation systems. A critical component of modern SR models
is the attention mechanism, which synthesizes users' historical activities.
This mechanism is typically order-invariant and generally relies on position
encoding (PE). Conventional SR models simply assign a learnable vector to each
position, resulting in only modest gains compared to traditional recommendation
models. Moreover, limited research has been conducted on position encoding
tailored for sequential recommendation, leaving a significant gap in addressing
its unique requirements. To bridge this gap, we propose a novel
Contextual-Aware Position Encoding method for sequential recommendation,
abbreviated as CAPE. To the best of our knowledge, CAPE is the first PE method
specifically designed for sequential recommendation. Comprehensive experiments
conducted on benchmark SR datasets demonstrate that CAPE consistently enhances
multiple mainstream backbone models and achieves state-of-the-art performance,
across small and large scale model size. Furthermore, we deployed CAPE in an
industrial setting on a real-world commercial platform, clearly showcasing the
effectiveness of our approach. Our source code is available at
https://github.com/yjdy/CAPE.
