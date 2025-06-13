---
layout: publication
title: 'Does RAG Really Perform Bad For Long-context Processing?'
authors: Kun Luo, Zheng Liu, Peitian Zhang, Hongjin Qian, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2025
bibkey: luo2025does
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11444'}
tags: ['RAG', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
The efficient processing of long context poses a serious challenge for large
language models (LLMs). Recently, retrieval-augmented generation (RAG) has
emerged as a promising strategy for this problem, as it enables LLMs to make
selective use of the long context for efficient computation. However, existing
RAG approaches lag behind other long-context processing methods due to inherent
limitations on inaccurate retrieval and fragmented contexts. To address these
challenges, we introduce RetroLM, a novel RAG framework for long-context
processing. Unlike traditional methods, RetroLM employs KV-level retrieval
augmentation, where it partitions the LLM's KV cache into contiguous pages and
retrieves the most crucial ones for efficient computation. This approach
enhances robustness to retrieval inaccuracy, facilitates effective utilization
of fragmented contexts, and saves the cost from repeated computation. Building
on this framework, we further develop a specialized retriever for precise
retrieval of critical pages and conduct unsupervised post-training to optimize
the model's ability to leverage retrieved information. We conduct comprehensive
evaluations with a variety of benchmarks, including LongBench, InfiniteBench,
and RULER, where RetroLM significantly outperforms existing long-context LLMs
and efficient long-context processing methods, particularly in tasks requiring
intensive reasoning or extremely long-context comprehension.
