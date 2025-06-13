---
layout: publication
title: 'Hybridbooth: Hybrid Prompt Inversion For Efficient Subject-driven Generation'
authors: Shanyan Guan, Yanhao Ge, Ying Tai, Jian Yang, Wei Li, Mingyu You
conference: "Arxiv"
year: 2024
bibkey: guan2024hybrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08192"}
tags: ['Tools', 'Efficiency and Optimization', 'Prompting', 'Merging']
---
Recent advancements in text-to-image diffusion models have shown remarkable
creative capabilities with textual prompts, but generating personalized
instances based on specific subjects, known as subject-driven generation,
remains challenging. To tackle this issue, we present a new hybrid framework
called HybridBooth, which merges the benefits of optimization-based and
direct-regression methods. HybridBooth operates in two stages: the Word
Embedding Probe, which generates a robust initial word embedding using a
fine-tuned encoder, and the Word Embedding Refinement, which further adapts the
encoder to specific subject images by optimizing key parameters. This approach
allows for effective and fast inversion of visual concepts into textual
embedding, even from a single image, while maintaining the model's
generalization capabilities.
