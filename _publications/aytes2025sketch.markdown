---
layout: publication
title: 'Sketch-of-thought: Efficient LLM Reasoning With Adaptive Cognitive-inspired Sketching'
authors: Simon A. Aytes, Jinheon Baek, Sung Ju Hwang
conference: "Arxiv"
year: 2025
bibkey: aytes2025sketch
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05179'}
tags: ['Prompting', 'Tools']
---
Recent advances in large language models (LLMs) have enabled strong reasoning capabilities through Chain-of-Thought (CoT) prompting, which elicits step-by-step problem solving, but often at the cost of excessive verbosity in intermediate outputs, leading to increased computational overhead. We propose Sketch-of-Thought (SoT), a prompting framework that integrates cognitively inspired reasoning paradigms with linguistic constraints to reduce token usage while preserving reasoning accuracy. SoT is designed as a flexible, modular approach and is instantiated with three paradigms--Conceptual Chaining, Chunked Symbolism, and Expert Lexicons--each tailored to distinct reasoning tasks and selected dynamically at test-time by a lightweight routing model. Across 15 reasoning datasets spanning multiple domains, languages, and modalities, SoT achieves token reductions of up to 78% with minimal accuracy loss. In tasks such as mathematical and multi-hop reasoning, it even improves accuracy while shortening outputs.
