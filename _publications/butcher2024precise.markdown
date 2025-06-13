---
layout: publication
title: 'Precise Length Control In Large Language Models'
authors: Bradley Butcher, Michael O'keefe, James Titchener
conference: "Precise length control for large language models Natural language processing Vol 11 (2025)"
year: 2024
bibkey: butcher2024precise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11937"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Large Language Models (LLMs) are increasingly used in production systems, powering applications such as chatbots, summarization, and question answering. Despite their success, controlling the length of their response remains a significant challenge, particularly for tasks requiring structured outputs or specific levels of detail. In this work, we propose a method to adapt pre-trained decoder-only LLMs for precise control of response length. Our approach incorporates a secondary length-difference positional encoding (LDPE) into the input embeddings, which counts down to a user-set response termination length. Fine-tuning with LDPE allows the model to learn to terminate responses coherently at the desired length, achieving mean token errors of less than 3 tokens. We also introduce Max New Tokens++, an extension that enables flexible upper-bound length control, rather than an exact target. Experimental results on tasks such as question answering and document summarization demonstrate that our method enables precise length control without compromising response quality.
