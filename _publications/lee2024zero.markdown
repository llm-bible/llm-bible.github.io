---
layout: publication
title: 'Zero-shot Multi-hop Question Answering Via Monte-carlo Tree Search With Large Language Models'
authors: Seongmin Lee, Jaewook Shin, Youngjin Ahn, Seokin Seo, Ohjoon Kwon, Kee-eung Kim
conference: "Arxiv"
year: 2024
bibkey: lee2024zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.19382'}
tags: ['Few-Shot', 'GPT', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advances in large language models (LLMs) have significantly impacted
the domain of multi-hop question answering (MHQA), where systems are required
to aggregate information and infer answers from disparate pieces of text.
However, the autoregressive nature of LLMs inherently poses a challenge as
errors may accumulate if mistakes are made in the intermediate reasoning steps.
This paper introduces Monte-Carlo tree search for Zero-shot multi-hop Question
Answering (MZQA), a framework based on Monte-Carlo tree search (MCTS) to
identify optimal reasoning paths in MHQA tasks, mitigating the error
propagation from sequential reasoning processes. Unlike previous works, we
propose a zero-shot prompting method, which relies solely on instructions
without the support of hand-crafted few-shot examples that typically require
domain expertise. We also introduce a behavioral cloning approach (MZQA-BC)
trained on self-generated MCTS inference trajectories, achieving an over
10-fold increase in reasoning speed with bare compromise in performance. The
efficacy of our method is validated on standard benchmarks such as HotpotQA,
2WikiMultihopQA, and MuSiQue, demonstrating that it outperforms existing
frameworks.
