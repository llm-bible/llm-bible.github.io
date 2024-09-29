---
layout: publication
title: Entropy Guided Extrapolative Decoding To Improve Factuality In Large Language Models
authors: Das Souvik, Jin Lifeng, Song Linfeng, Mi Haitao, Peng Baolin, Yu Dong
conference: "Arxiv"
year: 2024
bibkey: das2024entropy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09338"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) exhibit impressive natural language capabilities but suffer from hallucination 45;45; generating content ungrounded in the realities of training data. Recent work has focused on decoding techniques to improve factuality during inference by leveraging LLMs hierarchical representation of factual knowledge manipulating the predicted distributions at inference time. Current state45;of45;the45;art approaches refine decoding by contrasting early45;exit distributions from a lower layer with the final layer to exploit information related to factuality within the model forward procedure. However such methods often assume the final layer is the most reliable and the lower layer selection process depends on it. In this work we first propose extrapolation of critical token probabilities beyond the last layer for more accurate contrasting. We additionally employ layer45;wise entropy45;guided lower layer selection decoupling the selection process from the final layer. Experiments demonstrate strong performance 45; surpassing state45;of45;the45;art on multiple different datasets by large margins. Analyses show different kinds of prompts respond to different selection strategies.
