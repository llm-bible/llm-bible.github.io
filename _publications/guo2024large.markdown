---
layout: publication
title: Sillm\: Large Language Models For Simultaneous Machine Translation
authors: Guo Shoutao, Zhang Shaolei, Ma Zhengrui, Zhang Min, Feng Yang
conference: "Arxiv"
year: 2024
bibkey: guo2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13036"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Simultaneous Machine Translation (SiMT) generates translations while reading the source sentence necessitating a policy to determine the optimal timing for reading and generating words. Despite the remarkable performance achieved by Large Language Models (LLM) across various NLP tasks existing SiMT methods predominantly focus on conventional transformers employing a single model to concurrently determine the policy and generate the translations. However given the complexity of SiMT it is challenging to effectively address both tasks with a single model. Therefore there is a need to decouple the SiMT task into policy-decision and translation sub-tasks. We propose SiLLM which delegates the two sub-tasks to separate agents thereby incorporating LLM into SiMT. The policy-decision agent is managed by a conventional SiMT model responsible for determining the translation policy. The translation agent leveraging the capabilities of LLM generates translation using the partial source sentence. The two agents collaborate to accomplish SiMT. To facilitate the application of token-level policies determined by conventional SiMT models to LLM we propose a word-level policy adapted for LLM. Experiments on two datasets demonstrate that with a small amount of data for fine-tuning LLM SiLLM attains state-of-the-art performance.
