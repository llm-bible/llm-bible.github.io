---
layout: publication
title: 'Onioneval: An Unified Evaluation Of Fact-conflicting Hallucination For Small-large Language Models'
authors: Chongren Sun, Yuran Li, Di Wu, Benoit Boulet
conference: "Arxiv"
year: 2025
bibkey: sun2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12975"}
tags: ['Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) are highly capable but require significant
computational resources for both training and inference. Within the LLM family,
smaller models (those with fewer than 10 billion parameters) also perform well
across various tasks. However, these smaller models share similar limitations
to their larger counterparts, including the tendency to hallucinate. Despite
the existence of many benchmarks to evaluate hallucination in LLMs, few have
specifically focused on small LLMs (SLLMs). Additionally, SLLMs show widely
varying performance across different benchmarks. In this paper, we introduce
OnionEval, a multi-layer structured framework with a specific metric called the
context-influence score (CI), designed to effectively assess the
fact-conflicting hallucination tendencies of small LLMs across different
contextual levels. Our experimental results reveal a key feature of SLLMs: they
excel in factual analysis but face challenges with context reasoning. Further
investigation shows that a simple Chain-of-Thought strategy can significantly
reduce these limitations, improving the practical usefulness of SLLMs in
real-world applications.
