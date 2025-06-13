---
layout: publication
title: 'Don''t Let It Hallucinate: Premise Verification Via Retrieval-augmented Logical Reasoning'
authors: Yuehan Qin, Shawn Li, Yi Nian, Xinyan Velocity Yu, Yue Zhao, Xuezhe Ma
conference: "Arxiv"
year: 2025
bibkey: qin2025let
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.06438'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) have shown substantial capacity for generating
fluent, contextually appropriate responses. However, they can produce
hallucinated outputs, especially when a user query includes one or more false
premises-claims that contradict established facts. Such premises can mislead
LLMs into offering fabricated or misleading details. Existing approaches
include pretraining, fine-tuning, and inference-time techniques that often rely
on access to logits or address hallucinations after they occur. These methods
tend to be computationally expensive, require extensive training data, or lack
proactive mechanisms to prevent hallucination before generation, limiting their
efficiency in real-time applications. We propose a retrieval-based framework
that identifies and addresses false premises before generation. Our method
first transforms a user's query into a logical representation, then applies
retrieval-augmented generation (RAG) to assess the validity of each premise
using factual sources. Finally, we incorporate the verification results into
the LLM's prompt to maintain factual consistency in the final output.
Experiments show that this approach effectively reduces hallucinations,
improves factual accuracy, and does not require access to model logits or
large-scale fine-tuning.
