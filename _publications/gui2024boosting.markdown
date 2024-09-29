---
layout: publication
title: Boosting Lossless Speculative Decoding via Feature Sampling and Partial Alignment Distillation
authors: Gui Lujun, Xiao Bin, Su Lei, Chen Weipeng
conference: "Arxiv"
year: 2024
bibkey: gui2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15562"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'RAG', 'Tools', 'Training Techniques']
---
Lossless speculative decoding accelerates target large language model (LLM) inference by employing a lightweight draft model for generating tree-structured candidates which are subsequently verified in parallel by the target LLM. Currently effective approaches leverage feature-level rather than token-level autoregression within the draft model to facilitate more straightforward predictions and enhanced knowledge distillation. In this paper we reassess these approaches and propose FSPAD (Feature Sampling and Partial Alignment Distillation for Lossless Speculative Decoding) which introduces two straightforward and effective components within the existing framework to boost lossless speculative decoding. Firstly FSPAD utilizes token embeddings to sample features of the target LLM in high-dimensional space before feeding them into the draft model due to the inherent uncertainty of the features preventing the draft model from obtaining the specific token output by the target LLM. Secondly FSPAD introduces partial alignment distillation to weaken the draft models connection between features and logits aiming to reduce the conflict between feature alignment and logit confidence during training. Our experiments include both greedy and non-greedy decoding on the largest and smallest models from the Vicuna and LLaMA3-Instruct series as well as tasks in multi-turn conversation translation summarization question answering mathematical reasoning and retrieval-augmented generation. The results show that FSPAD outperforms the state-of-the-art method across all the aforementioned tasks and target LLMs.
