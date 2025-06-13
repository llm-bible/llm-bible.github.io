---
layout: publication
title: 'Accommodate Knowledge Conflicts In Retrieval-augmented Llms: Towards Reliable Response Generation In The Wild'
authors: Jiatai Wang, Zhiwei Xu, Di Jin, Xuewen Yang, Tao Li
conference: "Arxiv"
year: 2025
bibkey: wang2025accommodate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12982"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Applications']
---
The proliferation of large language models (LLMs) has significantly advanced
information retrieval systems, particularly in response generation (RG).
Unfortunately, LLMs often face knowledge conflicts between internal memory and
retrievaled external information, arising from misinformation, biases, or
outdated knowledge. These conflicts undermine response reliability and
introduce uncertainty in decision-making. In this work, we analyze how LLMs
navigate knowledge conflicts from an information-theoretic perspective and
reveal that when conflicting and supplementary information exhibit significant
differences, LLMs confidently resolve their preferences. However, when the
distinction is ambiguous, LLMs experience heightened uncertainty. Based on this
insight, we propose Swin-VIB, a novel framework that integrates a pipeline of
variational information bottleneck models into adaptive augmentation of
retrieved information and guiding LLM preference in response generation.
Extensive experiments on single-choice, open-ended question-answering (QA), and
retrieval augmented generation (RAG) validate our theoretical findings and
demonstrate the efficacy of Swin-VIB. Notably, our method improves
single-choice task accuracy by at least 7.54% over competitive baselines.
