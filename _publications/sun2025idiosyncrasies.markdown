---
layout: publication
title: 'Idiosyncrasies In Large Language Models'
authors: Mingjie Sun, Yida Yin, Zhiqiu Xu, J. Zico Kolter, Zhuang Liu
conference: "Arxiv"
year: 2025
bibkey: sun2025idiosyncrasies
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12150'}
  - {name: "Code", url: 'https://github.com/locuslab/llm-idiosyncrasies'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
In this work, we unveil and study idiosyncrasies in Large Language Models
(LLMs) -- unique patterns in their outputs that can be used to distinguish the
models. To do so, we consider a simple classification task: given a particular
text output, the objective is to predict the source LLM that generates the
text. We evaluate this synthetic task across various groups of LLMs and find
that simply fine-tuning existing text embedding models on LLM-generated texts
yields excellent classification accuracy. Notably, we achieve 97.1% accuracy on
held-out validation data in the five-way classification problem involving
ChatGPT, Claude, Grok, Gemini, and DeepSeek. Our further investigation reveals
that these idiosyncrasies are rooted in word-level distributions. These
patterns persist even when the texts are rewritten, translated, or summarized
by an external LLM, suggesting that they are also encoded in the semantic
content. Additionally, we leverage LLM as judges to generate detailed,
open-ended descriptions of each model's idiosyncrasies. Finally, we discuss the
broader implications of our findings, particularly for training on synthetic
data and inferring model similarity. Code is available at
https://github.com/locuslab/llm-idiosyncrasies.
