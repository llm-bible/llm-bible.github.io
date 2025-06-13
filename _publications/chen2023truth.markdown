---
layout: publication
title: 'Truth Forest: Toward Multi-scale Truthfulness In Large Language Models Through Intervention Without Tuning'
authors: Zhongzhi Chen, Xingwu Sun, Xianfeng Jiao, Fengzong Lian, Zhanhui Kang, Di Wang, Cheng-zhong Xu
conference: "Arxiv"
year: 2023
bibkey: chen2023truth
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17484"}
tags: ['Uncategorized']
---
Despite the great success of large language models (LLMs) in various tasks,
they suffer from generating hallucinations. We introduce Truth Forest, a method
that enhances truthfulness in LLMs by uncovering hidden truth representations
using multi-dimensional orthogonal probes. Specifically, it creates multiple
orthogonal bases for modeling truth by incorporating orthogonal constraints
into the probes. Moreover, we introduce Random Peek, a systematic technique
considering an extended range of positions within the sequence, reducing the
gap between discerning and generating truth features in LLMs. By employing this
approach, we improved the truthfulness of Llama-2-7B from 40.8% to 74.5% on
TruthfulQA. Likewise, significant improvements are observed in fine-tuned
models. We conducted a thorough analysis of truth features using probes. Our
visualization results show that orthogonal probes capture complementary
truth-related features, forming well-defined clusters that reveal the inherent
structure of the dataset.
