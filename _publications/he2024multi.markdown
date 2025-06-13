---
layout: publication
title: 'MINTQA: A Multi-hop Question Answering Benchmark For Evaluating Llms On New And Tail Knowledge'
authors: Jie He, Nan Hu, Wanqiu Long, Jiaoyan Chen, Jeff Z. Pan
conference: "Arxiv"
year: 2024
bibkey: he2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.17032'}
  - {name: "Code", url: 'https://github.com/probe2/multi-hop/'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code', 'Applications']
---
Large language models (LLMs) have demonstrated impressive capabilities in
various reasoning tasks but face significant challenges with complex,
knowledge-intensive multi-hop queries, particularly those involving new or
long-tail knowledge. Existing benchmarks often fail to fully address these
challenges. To bridge this gap, we introduce MINTQA (Multi-hop Question
Answering on New and Tail Knowledge), a comprehensive benchmark to evaluate
LLMs' capabilities in multi-hop reasoning across four critical dimensions:
question handling strategy, sub-question generation, retrieval-augmented
generation, and iterative or dynamic decomposition and retrieval. MINTQA
comprises 10,479 question-answer pairs for evaluating new knowledge and 17,887
pairs for assessing long-tail knowledge, with each question equipped with
corresponding sub-questions and answers. Our systematic evaluation of 22
state-of-the-art LLMs on MINTQA reveals significant limitations in their
ability to handle complex knowledge base queries, particularly in handling new
or unpopular knowledge. Our findings highlight critical challenges and offer
insights for advancing multi-hop reasoning capabilities. The MINTQA benchmark
is available at https://github.com/probe2/multi-hop/.
