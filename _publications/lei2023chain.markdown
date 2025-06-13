---
layout: publication
title: 'Chain Of Natural Language Inference For Reducing Large Language Model Ungrounded Hallucinations'
authors: Deren Lei, Yaxi Li, Mengya Hu, Mingyu Wang, Vincent Yun, Emily Ching, Eslam Kamal
conference: "Arxiv"
year: 2023
bibkey: lei2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03951"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Large language models (LLMs) can generate fluent natural language texts when
given relevant documents as background context. This ability has attracted
considerable interest in developing industry applications of LLMs. However,
LLMs are prone to generate hallucinations that are not supported by the
provided sources. In this paper, we propose a hierarchical framework to detect
and mitigate such ungrounded hallucination. Our framework uses Chain of Natural
Language Inference (CoNLI) for hallucination detection and hallucination
reduction via post-editing. Our approach achieves state-of-the-art performance
on hallucination detection and enhances text quality through rewrite, using
LLMs without any fine-tuning or domain-specific prompt engineering. We show
that this simple plug-and-play framework can serve as an effective choice for
hallucination detection and reduction, achieving competitive performance across
various contexts.
