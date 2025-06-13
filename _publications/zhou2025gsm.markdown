---
layout: publication
title: 'Gsm-infinite: How Do Your Llms Behave Over Infinitely Increasing Context Length And Reasoning Complexity?'
authors: Yang Zhou, Hongyi Liu, Zhuoming Chen, Yuandong Tian, Beidi Chen
conference: "Arxiv"
year: 2025
bibkey: zhou2025gsm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.05252'}
tags: ['Applications']
---
Long-context large language models (LLMs) have recently shown strong
performance in information retrieval and long-document QA. However, to tackle
the most challenging intellectual problems, LLMs must reason effectively in
long and complex contexts (e.g., frontier mathematical research). Studying how
LLMs handle increasing reasoning complexity and context length is essential,
yet existing benchmarks lack a solid basis for quantitative evaluation.
Inspired by the abstraction of GSM-8K problems as computational graphs, and the
ability to introduce noise by adding unnecessary nodes and edges, we develop a
grade school math problem generator capable of producing arithmetic problems
with infinite difficulty and context length under fine-grained control. Using
our newly synthesized GSM-Infinite benchmark, we comprehensively evaluate
existing LLMs. We find a consistent sigmoid decline in reasoning performance as
complexity increases, along with a systematic inference scaling trend:
exponentially increasing inference computation yields only linear performance
gains. These findings underscore the fundamental limitations of current
long-context LLMs and the key challenges in scaling reasoning capabilities. Our
GSM-Infinite benchmark provides a scalable and controllable testbed for
systematically studying and advancing LLM reasoning in long and complex
contexts.
