---
layout: publication
title: 'Preliminary Study On Incremental Learning For Large Language Model-based Recommender Systems'
authors: Shi Tianhao, Zhang Yang, Xu Zhijian, Chen Chong, Feng Fuli, He Xiangnan, Tian Qi
conference: "Arxiv"
year: 2023
bibkey: shi2023preliminary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15599"}
  - {name: "Code", url: "https://github.com/TianhaoShi2001/LSAT"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Adapting Large Language Models for Recommendation (LLM4Rec) has shown
promising results. However, the challenges of deploying LLM4Rec in real-world
scenarios remain largely unexplored. In particular, recommender models need
incremental adaptation to evolving user preferences, while the suitability of
traditional incremental learning methods within LLM4Rec remains ambiguous due
to the unique characteristics of Large Language Models (LLMs).
  In this study, we empirically evaluate two commonly employed incremental
learning strategies (full retraining and fine-tuning) for LLM4Rec.
Surprisingly, neither approach shows significant improvements in the
performance of LLM4Rec. Instead of dismissing the role of incremental learning,
we attribute the lack of anticipated performance enhancement to a mismatch
between the LLM4Rec architecture and incremental learning: LLM4Rec employs a
single adaptation module for learning recommendations, limiting its ability to
simultaneously capture long-term and short-term user preferences in the
incremental learning context. To test this speculation, we introduce a Long-
and Short-term Adaptation-aware Tuning (LSAT) framework for incremental
learning in LLM4Rec. Unlike the single adaptation module approach, LSAT
utilizes two distinct adaptation modules to independently learn long-term and
short-term user preferences. Empirical results verify that LSAT enhances
performance, thereby validating our speculation. We release our code at:
https://github.com/TianhaoShi2001/LSAT.
