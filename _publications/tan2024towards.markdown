---
layout: publication
title: 'Teola: Towards End-to-end Optimization Of Llm-based Applications'
authors: Xin Tan, Yimin Jiang, Yitao Yang, Hong Xu
conference: "Arxiv"
year: 2024
bibkey: tan2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00326"}
  - {name: "Code", url: "https://github.com/NetX-lab/Ayo"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Large-Scale Training', 'Has Code', 'Applications']
---
Large language model (LLM)-based applications consist of both LLM and non-LLM
components, each contributing to the end-to-end latency. Despite great efforts
to optimize LLM inference, end-to-end workflow optimization has been
overlooked. Existing frameworks employ coarse-grained orchestration with task
modules, which confines optimizations to within each module and yields
suboptimal scheduling decisions. We propose fine-grained end-to-end
orchestration, which utilizes task primitives as the basic units and represents
each query's workflow as a primitive-level dataflow graph. This explicitly
exposes a much larger design space, enables optimizations in parallelization
and pipelining across primitives of different modules, and enhances scheduling
to improve application-level performance. We build Teola, a novel orchestration
framework for LLM-based applications that implements this scheme. Comprehensive
experiments show that Teola can achieve up to 2.09x speedup over existing
systems across various popular LLM applications. The code is available at
https://github.com/NetX-lab/Ayo.
