---
layout: publication
title: 'Unleashing The Power Of Large Language Models For Group POI Recommendations'
authors: Jing Long, Liang Qu, Guanhua Ye, Tong Chen, Quoc Viet Hung Nguyen, Hongzhi Yin
conference: "Arxiv"
year: 2024
bibkey: long2024unleashing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.13415'}
tags: ['Training Techniques', 'Fine-Tuning', 'Tools', 'Pretraining Methods']
---
Group Point-of-Interest (POI) recommendations aim to predict the next POI
that satisfies the diverse preferences of a group of users. This task is more
challenging than traditional individual POI recommendations due to complex
group decision-making and extremely sparse group-level check-in data. Existing
methods for group POI recommendations primarily rely on single ID-based
features from check-in data, capturing only statistical correlations and
failing to fully utilize the rich semantic information contained in the
check-ins, resulting in suboptimal performance. To this end, we propose a
framework that unleashes the power of the Large Language Model (LLM) for
context-aware group POI recommendations (LLMGPR). Our approach first introduces
POI tokens alongside the original word tokens of the LLM, which are initialized
by applying the LLM to the rich information of each POI. We then propose a
novel sequencing adapter guided by Quantized Low-Rank Adaptation (QLORA) to
modify the LLM. The enhanced LLM can learn sequence representations by
combining semantic-enhanced POI tokens and rich contextual information
including positional encodings and spatio-temporal differences. This approach
can be adapted for learning either group or user representations depending on
the sequence type. Furthermore, we enhance group representations by aggregating
individual member representations with another QLORA-based aggregation adapter
and introducing a self-supervised learning task that predicts the purpose of
check-in sequences, alleviating the data sparsity issue. Our experimental
results demonstrate that LLMGPR outperforms existing methods, effectively
addressing group-level data sparsity and providing superior recommendations.
