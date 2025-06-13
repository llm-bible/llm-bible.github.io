---
layout: publication
title: 'Parameters Vs. Context: Fine-grained Control Of Knowledge Reliance In Language Models'
authors: Baolong Bi, Shenghua Liu, Yiwei Wang, Yilong Xu, Junfeng Fang, Lingrui Mei, Xueqi Cheng
conference: "Arxiv"
year: 2025
bibkey: bi2025parameters
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.15888'}
  - {name: "Code", url: 'https://github.com/byronBBL/CK-PLUG}{{this'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code']
---
Retrieval-Augmented Generation (RAG) mitigates hallucinations in Large
Language Models (LLMs) by integrating external knowledge. However, conflicts
between parametric knowledge and retrieved context pose challenges,
particularly when retrieved information is unreliable or the model's internal
knowledge is outdated. In such cases, LLMs struggle to determine whether to
rely more on their own parameters or the conflicted context. To address this,
we propose **CK-PLUG**, a plug-and-play method for controlling LLMs' reliance
on parametric and contextual knowledge. We introduce a novel knowledge
consistency metric, Confidence Gain, which detects knowledge conflicts by
measuring entropy shifts in token probability distributions after context
insertion. CK-PLUG then enables fine-grained control over knowledge preference
by adjusting the probability distribution of tokens with negative confidence
gain through a single tuning parameter. Experiments demonstrate CK-PLUG's
ability to significantly regulate knowledge reliance in counterfactual RAG
scenarios while maintaining generation fluency and knowledge accuracy. For
instance, on Llama3-8B, memory recall (MR) of RAG response can be adjusted
within a broad range (9.9%-71.9%), compared to the baseline of 42.1%. Moreover,
CK-PLUG supports adaptive control based on the model's confidence in both
internal and external knowledge, achieving consistent performance improvements
across various general RAG tasks. Our code is available at:
\\(\href\{https://github.com/byronBBL/CK-PLUG\}\{\text\{this https URL\}\}\\).
