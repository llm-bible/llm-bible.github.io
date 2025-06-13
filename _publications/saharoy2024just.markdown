---
layout: publication
title: 'Don''t Just Pay Attention, PLANT It: Transfer L2R Models To Fine-tune Attention In Extreme Multi-label Text Classification'
authors: Debjyoti Saharoy, Javed A. Aslam, Virgil Pavlu
conference: "Arxiv"
year: 2024
bibkey: saharoy2024just
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23066'}
tags: ['Attention Mechanism', 'Transformer', 'Few-Shot', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
State-of-the-art Extreme Multi-Label Text Classification (XMTC) models rely
heavily on multi-label attention layers to focus on key tokens in input text,
but obtaining optimal attention weights is challenging and resource-intensive.
To address this, we introduce PLANT -- Pretrained and Leveraged AtteNTion -- a
novel transfer learning strategy for fine-tuning XMTC decoders. PLANT surpasses
existing state-of-the-art methods across all metrics on mimicfull, mimicfifty,
mimicfour, eurlex, and wikiten datasets. It particularly excels in few-shot
scenarios, outperforming previous models specifically designed for few-shot
scenarios by over 50 percentage points in F1 scores on mimicrare and by over 36
percentage points on mimicfew, demonstrating its superior capability in
handling rare codes. PLANT also shows remarkable data efficiency in few-shot
scenarios, achieving precision comparable to traditional models with
significantly less data. These results are achieved through key technical
innovations: leveraging a pretrained Learning-to-Rank model as the planted
attention layer, integrating mutual-information gain to enhance attention,
introducing an inattention mechanism, and implementing a stateful-decoder to
maintain context. Comprehensive ablation studies validate the importance of
these contributions in realizing the performance gains.
