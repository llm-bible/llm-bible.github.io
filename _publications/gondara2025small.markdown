---
layout: publication
title: 'Small Or Large? Zero-shot Or Finetuned? Guiding Language Model Choice For Specialized Applications In Healthcare'
authors: Lovedeep Gondara, Jonathan Simkin, Graham Sayle, Shebnum Devji, Gregory Arbour, Raymond Ng
conference: "Arxiv"
year: 2025
bibkey: gondara2025small
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21191'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Applications', 'Pretraining Methods']
---
This study aims to guide language model selection by investigating: 1) the
necessity of finetuning versus zero-shot usage, 2) the benefits of
domain-adjacent versus generic pretrained models, 3) the value of further
domain-specific pretraining, and 4) the continued relevance of Small Language
Models (SLMs) compared to Large Language Models (LLMs) for specific tasks.
Using electronic pathology reports from the British Columbia Cancer Registry
(BCCR), three classification scenarios with varying difficulty and data size
are evaluated. Models include various SLMs and an LLM. SLMs are evaluated both
zero-shot and finetuned; the LLM is evaluated zero-shot only. Finetuning
significantly improved SLM performance across all scenarios compared to their
zero-shot results. The zero-shot LLM outperformed zero-shot SLMs but was
consistently outperformed by finetuned SLMs. Domain-adjacent SLMs generally
performed better than the generic SLM after finetuning, especially on harder
tasks. Further domain-specific pretraining yielded modest gains on easier tasks
but significant improvements on the complex, data-scarce task. The results
highlight the critical role of finetuning for SLMs in specialized domains,
enabling them to surpass zero-shot LLM performance on targeted classification
tasks. Pretraining on domain-adjacent or domain-specific data provides further
advantages, particularly for complex problems or limited finetuning data. While
LLMs offer strong zero-shot capabilities, their performance on these specific
tasks did not match that of appropriately finetuned SLMs. In the era of LLMs,
SLMs remain relevant and effective, offering a potentially superior
performance-resource trade-off compared to LLMs.
