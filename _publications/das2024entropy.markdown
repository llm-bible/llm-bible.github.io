---
layout: publication
title: 'Entropy Guided Extrapolative Decoding To Improve Factuality In Large Language Models'
authors: Souvik Das, Lifeng Jin, Linfeng Song, Haitao Mi, Baolin Peng, Dong Yu
conference: "Arxiv"
year: 2024
bibkey: das2024entropy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09338"}
tags: ['RAG', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) exhibit impressive natural language capabilities
but suffer from hallucination -- generating content ungrounded in the realities
of training data. Recent work has focused on decoding techniques to improve
factuality during inference by leveraging LLMs' hierarchical representation of
factual knowledge, manipulating the predicted distributions at inference time.
Current state-of-the-art approaches refine decoding by contrasting early-exit
distributions from a lower layer with the final layer to exploit information
related to factuality within the model forward procedure. However, such methods
often assume the final layer is the most reliable and the lower layer selection
process depends on it. In this work, we first propose extrapolation of critical
token probabilities beyond the last layer for more accurate contrasting. We
additionally employ layer-wise entropy-guided lower layer selection, decoupling
the selection process from the final layer. Experiments demonstrate strong
performance - surpassing state-of-the-art on multiple different datasets by
large margins. Analyses show different kinds of prompts respond to different
selection strategies.
