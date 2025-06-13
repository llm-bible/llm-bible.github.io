---
layout: publication
title: 'Aixcoder-7b: A Lightweight And Effective Large Language Model For Code Processing'
authors: Siyuan Jiang, Jia Li, He Zong, Huanyu Liu, Hao Zhu, Shukai Hu, Erlu Li, Jiazheng Ding, Yu Han, Wei Ning, Gen Wang, Yihong Dong, Kechi Zhang, Ge Li
conference: "Arxiv"
year: 2024
bibkey: jiang2024aixcoder
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13187'}
tags: ['Attention Mechanism', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture']
---
Large Language Models (LLMs) have been widely used in code completion, and
researchers are focusing on scaling up LLMs to improve their accuracy. However,
larger LLMs have lower inference efficiency, affecting developers' experience
and productivity. In this paper, we propose a lightweight and effective LLM for
code completion named aiXcoder-7B. Compared to existing LLMs, aiXcoder-7B
achieves higher code completion accuracy while having smaller scales (i.e., 7
billion parameters). We attribute the superiority of aiXcoder-7B to three key
factors: (1) Multi-objective training. We employ three training objectives, one
of which is our proposed Structured Fill-In-the-Middle (SFIM). SFIM considers
the syntax structures in code and effectively improves the performance of LLMs
for code. (2) Diverse data sampling strategies. They consider inter-file
relationships and enhance the capability of LLMs in understanding cross-file
contexts. (3) Extensive high-quality data. We establish a rigorous data
collection pipeline and consume a total of 1.2 trillion unique tokens for
training aiXcoder-7B. This vast volume of data enables aiXcoder-7B to learn a
broad distribution of code. We evaluate aiXcoder-7B in five popular code
completion benchmarks and a new benchmark collected by this paper. The results
show that aiXcoder-7B outperforms the latest six LLMs with similar sizes and
even surpasses four larger LLMs (e.g., StarCoder2-15B and CodeLlama-34B),
positioning aiXcoder-7B as a lightweight and effective LLM for academia and
industry. Finally, we summarize three valuable insights for helping
practitioners train the next generations of LLMs for code. aiXcoder-7B has been
open-souced and gained significant attention. Until January 2025, aiXcoder-7B
has received 2,226 GitHub Stars.
