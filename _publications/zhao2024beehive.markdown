---
layout: publication
title: 'BUZZ: Beehive-structured Sparse KV Cache With Segmented Heavy Hitters For Efficient LLM Inference'
authors: Junqi Zhao, Zhijin Fang, Shu Li, Shaohui Yang, Shichao He
conference: "Arxiv"
year: 2024
bibkey: zhao2024beehive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23079'}
  - {name: "Code", url: 'https://github.com/JunqiZhao888/buzz-llm'}
tags: ['Has Code', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) are essential in natural language processing but
often struggle with inference speed and computational efficiency, limiting
real-time deployment. The key-value (KV) cache mechanism reduces computational
overhead in transformer models, but challenges in maintaining contextual
understanding remain. In this paper, we propose BUZZ, a novel KV caching
algorithm that leverages structured contextual information to minimize cache
memory usage while enhancing inference speed. BUZZ employs a beehive-structured
sparse cache, incorporating a sliding window to capture recent information and
dynamically segmenting historical tokens into chunks to prioritize important
tokens in local neighborhoods. We evaluate BUZZ on four real-world datasets:
CNN/Daily Mail, XSUM, Wikitext, and 10-QA. Our results demonstrate that BUZZ
(1) reduces cache memory usage by \\(\textbf\{2.5\}\times\\) in LLM inference while
maintaining over 99% accuracy in long-text summarization, and (2) surpasses
state-of-the-art performance in multi-document question answering by
\\(\textbf\{7.69%\}\\) under the same memory limit, where full cache methods
encounter out-of-memory issues. Additionally, BUZZ achieves significant
inference speedup with a \\(log\{n\}\\) time complexity. The code is available at
https://github.com/JunqiZhao888/buzz-llm.
