---
layout: publication
title: 'Data-centric Financial Large Language Models'
authors: Zhixuan Chu, Huaiyu Guo, Xinyuan Zhou, Yijia Wang, Fei Yu, Hong Chen, Wanqing Xu, Xin Lu, Qing Cui, Longfei Li, Jun Zhou, Sheng Li
conference: "Arxiv"
year: 2023
bibkey: chu2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17784"}
tags: ['Training Techniques', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) show promise for natural language tasks but
struggle when applied directly to complex domains like finance. LLMs have
difficulty reasoning about and integrating all relevant information. We propose
a data-centric approach to enable LLMs to better handle financial tasks. Our
key insight is that rather than overloading the LLM with everything at once, it
is more effective to preprocess and pre-understand the data. We create a
financial LLM (FLLM) using multitask prompt-based finetuning to achieve data
pre-processing and pre-understanding. However, labeled data is scarce for each
task. To overcome manual annotation costs, we employ abductive augmentation
reasoning (AAR) to automatically generate training data by modifying the pseudo
labels from FLLM's own outputs. Experiments show our data-centric FLLM with AAR
substantially outperforms baseline financial LLMs designed for raw text,
achieving state-of-the-art on financial analysis and interpretation tasks. We
also open source a new benchmark for financial analysis and interpretation. Our
methodology provides a promising path to unlock LLMs' potential for complex
real-world domains.
