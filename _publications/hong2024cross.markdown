---
layout: publication
title: 'Cross-lingual Transfer Of Reward Models In Multilingual Alignment'
authors: Jiwoo Hong, Noah Lee, Rodrigo Martínez-castaño, César Rodríguez, James Thorne
conference: "Arxiv"
year: 2024
bibkey: hong2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18027"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning']
---
Reinforcement learning with human feedback (RLHF) is shown to largely benefit
from precise reward models (RMs). However, recent studies in reward modeling
schemes are skewed towards English, limiting the applicability of RLHF in
multilingual alignments. In this work, we investigate the cross-lingual
transfer of RMs trained in diverse languages, primarily from English. Our
experimental results demonstrate the strong cross-lingual transfer of English
RMs, exceeding target language RMs by 3~4% average increase in Multilingual
RewardBench. Furthermore, we analyze the cross-lingual transfer of RMs through
the representation shifts. Finally, we perform multilingual alignment to
exemplify how cross-lingual transfer in RM propagates to enhanced multilingual
instruction-following capability, along with extensive analyses on
off-the-shelf RMs. We release the code, model, and data.
