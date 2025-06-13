---
layout: publication
title: 'ARN: Analogical Reasoning On Narratives'
authors: Zhivar Sourati, Filip Ilievski, Pia Sommerauer, Yifan Jiang
conference: "Arxiv"
year: 2023
bibkey: sourati2023analogical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00996"}
tags: ['Model Architecture', 'Few-Shot', 'Tools', 'RAG', 'GPT']
---
As a core cognitive skill that enables the transferability of information
across domains, analogical reasoning has been extensively studied for both
humans and computational models. However, while cognitive theories of analogy
often focus on narratives and study the distinction between surface,
relational, and system similarities, existing work in natural language
processing has a narrower focus as far as relational analogies between word
pairs. This gap brings a natural question: can state-of-the-art large language
models (LLMs) detect system analogies between narratives? To gain insight into
this question and extend word-based relational analogies to relational system
analogies, we devise a comprehensive computational framework that
operationalizes dominant theories of analogy, using narrative elements to
create surface and system mappings. Leveraging the interplay between these
mappings, we create a binary task and benchmark for Analogical Reasoning on
Narratives (ARN), covering four categories of far (cross-domain)/near
(within-domain) analogies and disanalogies. We show that while all LLMs can
largely recognize near analogies, even the largest ones struggle with far
analogies in a zero-shot setting, with GPT4.0 scoring below random. Guiding the
models through solved examples and chain-of-thought reasoning enhances their
analogical reasoning ability. Yet, since even in the few-shot setting, the best
model only performs halfway between random and humans, ARN opens exciting
directions for computational analogical reasoners.
