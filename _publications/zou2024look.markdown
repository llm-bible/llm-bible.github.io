---
layout: publication
title: 'Look Twice Before You Answer: Memory-space Visual Retracing For Hallucination Mitigation In Multimodal Large Language Models'
authors: Xin Zou, Yizhou Wang, Yibo Yan, Yuanhuiyi Lyu, Kening Zheng, Sirui Huang, Junkai Chen, Peijie Jiang, Jia Liu, Chang Tang, Xuming Hu
conference: "Arxiv"
year: 2024
bibkey: zou2024look
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03577'}
  - {name: "Code", url: 'https://github.com/1zhou-Wang/MemVR'}
tags: ['Has Code', 'Multimodal Models']
---
Despite their impressive capabilities, multimodal large language models
(MLLMs) are prone to hallucinations, i.e., the generated content that is
nonsensical or unfaithful to input sources. Unlike in LLMs, hallucinations in
MLLMs often stem from the sensitivity of text decoder to visual tokens, leading
to a phenomenon akin to "amnesia" about visual information. To address this
issue, we propose MemVR, a novel decoding paradigm inspired by common
cognition: when the memory of an image seen the moment before is forgotten,
people will look at it again for factual answers. Following this principle, we
treat visual tokens as supplementary evidence, re-injecting them into the MLLM
through Feed Forward Network (FFN) as "key-value memory" at the middle trigger
layer. This "look-twice" mechanism occurs when the model exhibits high
uncertainty during inference, effectively enhancing factual alignment.
Comprehensive experimental evaluations demonstrate that MemVR significantly
mitigates hallucination across various MLLMs and excels in general benchmarks
without incurring additional time overhead. The implementation is available
from https://github.com/1zhou-Wang/MemVR
