---
layout: publication
title: 'Direct Retrieval-augmented Optimization: Synergizing Knowledge Selection And Language Models'
authors: Zhengliang Shi, Lingyong Yan, Weiwei Sun, Yue Feng, Pengjie Ren, Xinyu Ma, Shuaiqiang Wang, Dawei Yin, Maarten De Rijke, Zhaochun Ren
conference: "Arxiv"
year: 2025
bibkey: shi2025direct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03075"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
Retrieval-augmented generation (RAG) integrates large language models ( LLM
s) with retrievers to access external knowledge, improving the factuality of
LLM generation in knowledge-grounded tasks. To optimize the RAG performance,
most previous work independently fine-tunes the retriever to adapt to frozen
LLM s or trains the LLMs to use documents retrieved by off-the-shelf
retrievers, lacking end-to-end training supervision. Recent work addresses this
limitation by jointly training these two components but relies on overly
simplifying assumptions of document independence, which has been criticized for
being far from real-world scenarios. Thus, effectively optimizing the overall
RAG performance remains a critical challenge.
  We propose a direct retrieval-augmented optimization framework, named DRO,
that enables end-to-end training of two key components: (i) a generative
knowledge selection model and (ii) an LLM generator. DRO alternates between two
phases: (i) document permutation estimation and (ii) re-weighted maximization,
progressively improving RAG components through a variational approach. In the
estimation step, we treat document permutation as a latent variable and
directly estimate its distribution from the selection model by applying an
importance sampling strategy. In the maximization step, we calibrate the
optimization expectation using importance weights and jointly train the
selection model and LLM generator. Our theoretical analysis reveals that DRO is
analogous to policy-gradient methods in reinforcement learning. Extensive
experiments conducted on five datasets illustrate that DRO outperforms the best
baseline with 5%-15% improvements in EM and F1. We also provide in-depth
experiments to qualitatively analyze the stability, convergence, and variance
of DRO.
