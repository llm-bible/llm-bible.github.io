---
layout: publication
title: 'Cream Of The Crop: Harvesting Rich, Scalable And Transferable Multi-modal Data For Instruction Fine-tuning'
authors: Mengyao Lyu, Yan Li, Huasong Zhong, Wenhao Yang, Hui Chen, Jungong Han, Guiguang Ding, Zhenheng Yang
conference: "Arxiv"
year: 2025
bibkey: lyu2025cream
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13383'}
tags: ['Security', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
The hypothesis that pretrained large language models (LLMs) necessitate only
minimal supervision during the fine-tuning (SFT) stage (Zhou et al., 2024) has
been substantiated by recent advancements in data curation and selection
research. However, their stability and generalizability are compromised due to
the vulnerability to experimental setups and validation protocols, falling
short of surpassing random sampling (Diddee & Ippolito, 2024; Xia et al.,
2024b). Built upon LLMs, multi-modal LLMs (MLLMs), combined with the sheer
token volume and heightened heterogeneity of data sources, amplify both the
significance and complexity of data selection.
  To harvest multi-modal instructional data in a robust and efficient manner,
we re-define the granularity of the quality metric by decomposing it into 14
vision-language-related capabilities, and introduce multi-modal rich scorers to
evaluate the capabilities of each data candidate. To promote diversity, in
light of the inherent objective of the alignment stage, we take interaction
style as diversity indicator and use a multi-modal rich styler to identify data
instruction patterns. In doing so, our multi-modal rich scorers and styler
(mmSSR) guarantee that high-scoring information is conveyed to users in
diversified forms. Free from embedding-based clustering or greedy sampling,
mmSSR efficiently scales to millions of data with varying budget constraints,
supports customization for general or specific capability acquisition, and
facilitates training-free generalization to new domains for curation. Across
10+ experimental settings, validated by 14 multi-modal benchmarks, we
demonstrate consistent improvements over random sampling, baseline strategies
and state-of-the-art selection methods, achieving 99.1% of full performance
with only 30% of the 2.6M data.
