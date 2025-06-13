---
layout: publication
title: 'Sessionrec: Next Session Prediction Paradigm For Generative Sequential Recommendation'
authors: Lei Huang, Hao Guo, Linzhi Peng, Long Zhang, Xiaoteng Wang, Daoyuan Wang, Shichao Wang, Jinpeng Wang, Lei Wang, Sheng Chen
conference: "Arxiv"
year: 2025
bibkey: huang2025next
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10157'}
tags: ['Attention Mechanism', 'Large-Scale Training', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'Scaling Laws', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
We introduce SessionRec, a novel next-session prediction paradigm (NSPP) for
generative sequential recommendation, addressing the fundamental misalignment
between conventional next-item prediction paradigm (NIPP) and real-world
recommendation scenarios. Unlike NIPP's item-level autoregressive generation
that contradicts actual session-based user interactions, our framework
introduces a session-aware representation learning through hierarchical
sequence aggregation (intra/inter-session), reducing attention computation
complexity while enabling implicit modeling of massive negative interactions,
and a session-based prediction objective that better captures users' diverse
interests through multi-item recommendation in next sessions. Moreover, we
found that incorporating a rank loss for items within the session under the
next session prediction paradigm can significantly improve the ranking
effectiveness of generative sequence recommendation models. We also verified
that SessionRec exhibits clear power-law scaling laws similar to those observed
in LLMs. Extensive experiments conducted on public datasets and online A/B test
in Meituan App demonstrate the effectiveness of SessionRec. The proposed
paradigm establishes new foundations for developing industrial-scale generative
recommendation systems through its model-agnostic architecture and
computational efficiency.
