---
layout: publication
title: 'Metatextgrad: Automatically Optimizing Language Model Optimizers'
authors: Guowei Xu, Mert Yuksekgonul, Carlos Guestrin, James Zou
conference: "Arxiv"
year: 2025
bibkey: xu2025automatically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18524"}
tags: ['Prompting', 'Efficiency and Optimization', 'RAG', 'Tools']
---
Large language models (LLMs) are increasingly used in learning algorithms, evaluations, and optimization tasks. Recent studies have shown that using LLM-based optimizers to automatically optimize model prompts, demonstrations, predictions themselves, or other components can significantly enhance the performance of AI systems, as demonstrated by frameworks such as DSPy and TextGrad. However, optimizers built on language models themselves are usually designed by humans with manual design choices; optimizers themselves are not optimized. Moreover, these optimizers are general purpose by design, to be useful to a broad audience, and are not tailored for specific tasks. To address these challenges, we propose metaTextGrad, which focuses on designing a meta-optimizer to further enhance existing optimizers and align them to be good optimizers for a given task. Our approach consists of two key components: a meta prompt optimizer and a meta structure optimizer. The combination of these two significantly improves performance across multiple benchmarks, achieving an average absolute performance improvement of up to 6% compared to the best baseline.
