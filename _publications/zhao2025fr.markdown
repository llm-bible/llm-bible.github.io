---
layout: publication
title: 'Fr-spec: Accelerating Large-vocabulary Language Models Via Frequency-ranked Speculative Sampling'
authors: Weilin Zhao, Tengyu Pan, Xu Han, Yudi Zhang, Ao Sun, Yuxiang Huang, Kaihuo Zhang, Weilun Zhao, Yuxuan Li, Jianyong Wang, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: zhao2025fr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14856"}
  - {name: "Code", url: "https://github.com/thunlp/FR-Spec"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Language Modeling', 'RAG', 'Has Code']
---
Speculative sampling has emerged as an important technique for accelerating
the auto-regressive generation process of large language models (LLMs) by
utilizing a draft-then-verify mechanism to produce multiple tokens per forward
pass. While state-of-the-art speculative sampling methods use only a single
layer and a language modeling (LM) head as the draft model to achieve
impressive layer compression, their efficiency gains are substantially reduced
for large-vocabulary LLMs, such as Llama-3-8B with a vocabulary of 128k tokens.
To address this, we present FR-Spec, a frequency-ranked speculative sampling
framework that optimizes draft candidate selection through vocabulary space
compression. By constraining the draft search to a frequency-prioritized token
subset, our method reduces LM Head computation overhead by 75% while ensuring
the equivalence of the final output distribution. Experiments across multiple
datasets demonstrate an average of 1.12\\(\times\\) speedup over the
state-of-the-art speculative sampling method EAGLE-2. Code available at
https://github.com/thunlp/FR-Spec.
