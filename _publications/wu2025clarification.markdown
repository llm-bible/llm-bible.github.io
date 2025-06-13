---
layout: publication
title: 'Clarifycoder: Clarification-aware Fine-tuning For Programmatic Problem Solving'
authors: Jie Jw Wu, Manav Chaudhary, Davit Abrahamyan, Arhaan Khaku, Anjiang Wei, Fatemeh H. Fard
conference: "Arxiv"
year: 2025
bibkey: wu2025clarification
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16331"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
code generation tasks. However, a significant gap remains between their current
performance and that of expert software engineers. A key differentiator is that
human engineers actively seek clarification when faced with ambiguous
requirements, while LLMs typically generate code regardless of uncertainties in
the problem description. We present ClarifyCoder, a novel framework with
synthetic data generation and instruction-tuning that enables LLMs to identify
ambiguities and request clarification before proceeding with code generation.
While recent work has focused on LLM-based agents for iterative code
generation, we argue that the fundamental ability to recognize and query
ambiguous requirements should be intrinsic to the models themselves. Our
approach consists of two main components: (1) a data synthesis technique that
augments existing programming datasets with scenarios requiring clarification
to generate clarification-aware training data, and (2) a fine-tuning strategy
that teaches models to prioritize seeking clarification over immediate code
generation when faced with incomplete or ambiguous requirements. We further
provide an empirical analysis of integrating ClarifyCoder with standard
fine-tuning for a joint optimization of both clarify-awareness and coding
ability. Experimental results demonstrate that ClarifyCoder significantly
improves the communication capabilities of Code LLMs through meaningful
clarification dialogues while maintaining code generation capabilities.
