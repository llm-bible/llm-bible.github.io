---
layout: publication
title: 'Pixelworld: Towards Perceiving Everything As Pixels'
authors: Zhiheng Lyu, Xueguang Ma, Wenhu Chen
conference: "Arxiv"
year: 2025
bibkey: lyu2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.19339"}
tags: ['Fine-Tuning', 'Transformer', 'Agentic', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Recent agentic language models increasingly need to interact directly with real-world environments containing intertwined visual and textual information through raw camera pixels, rather than relying on separate image and tokenized text processing, underscoring the necessity of a unified perception paradigm. To close this gap, we explore this idea through Perceive Everything as Pixels (PEAP) and release PixelWorld, a benchmark that renders natural-language, tabular, mathematical and diagrammatic inputs into a single pixel space. Experiments show that PEAP attains competitive accuracy on semantic-understanding tasks, indicating that a vision transformer can capture global textual semantics without explicit tokens. In contrast, reasoning-intensive benchmarks (math and code) exhibit sharp performance drops; however, Chain-of-Thought prompting partially mitigates this gap, hinting that explicit reasoning traces compensate for the missing token structure. We also find that when visual and textual information are closely integrated, representing everything as pixels reduces preprocessing complexity and avoids misalignment issues that often arise in separate pipelines. PixelWorld therefore serves as a practical benchmark for evaluating unified vision-language models and supports broader exploration of PEAP across diverse tasks.
