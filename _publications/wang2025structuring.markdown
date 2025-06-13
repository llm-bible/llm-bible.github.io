---
layout: publication
title: 'SLOT: Structuring The Output Of Large Language Models'
authors: Darren Yow-bang Wang, Zhengyuan Shen, Soumya Smruti Mishra, Zhichao Xu, Yifei Teng, Haibo Ding
conference: "Arxiv"
year: 2025
bibkey: wang2025structuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04016"}
tags: ['Transformer', 'Agentic', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Structured outputs are essential for large language models (LLMs) in critical
applications like agents and information extraction. Despite their
capabilities, LLMs often generate outputs that deviate from predefined schemas,
significantly hampering reliable application development. We present SLOT
(Structured LLM Output Transformer), a model-agnostic approach that transforms
unstructured LLM outputs into precise structured formats. While existing
solutions predominantly rely on constrained decoding techniques or are tightly
coupled with specific models, SLOT employs a fine-tuned lightweight language
model as a post-processing layer, achieving flexibility across various LLMs and
schema specifications. We introduce a systematic pipeline for data curation and
synthesis alongside a formal evaluation methodology that quantifies both schema
accuracy and content fidelity. Our results demonstrate that fine-tuned
Mistral-7B model with constrained decoding achieves near perfect schema
accuracy (99.5%) and content similarity (94.0%), outperforming
Claude-3.5-Sonnet by substantial margins (+25 and +20 percentage points,
respectively). Notably, even compact models like Llama-3.2-1B can match or
exceed the structured output capabilities of much larger proprietary models
when equipped with SLOT, enabling reliable structured generation in
resource-constrained environments.
