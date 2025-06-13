---
layout: publication
title: 'Fusechat-3.0: Preference Optimization Meets Heterogeneous Model Fusion'
authors: Ziyi Yang, Fanqi Wan, Longguang Zhong, Canbin Huang, Guosheng Liang, Xiaojun Quan
conference: "Arxiv"
year: 2025
bibkey: yang2025fusechat
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04222'}
  - {name: "Code", url: 'https://github.com/SLIT-AI/FuseChat-3.0'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Merging', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
We introduce FuseChat-3.0, a suite of large language models (LLMs) developed
by integrating the strengths of heterogeneous source LLMs into more compact
target LLMs. Our source models include the powerful Gemma-2-27B-it,
Mistral-Large-Instruct-2407, Qwen-2.5-72B-Instruct, and Llama-3.1-70B-Instruct.
For target models, we focus on three widely-used smaller
variants-Llama-3.1-8B-Instruct, Gemma-2-9B-it, and Qwen-2.5-7B-Instruct-along
with two ultra-compact options, Llama-3.2-3B-Instruct and
Llama-3.2-1B-Instruct. To leverage the diverse capabilities of these source
models, we develop a specialized data construction protocol tailored to various
tasks and domains. The FuseChat-3.0 training pipeline consists of two key
stages: (1) supervised fine-tuning (SFT) to align the target and source model
distributions, and (2) Direct Preference Optimization (DPO) to apply
preferences from multiple source LLMs to fine-tune the target model. The
resulting FuseChat-3.0 models exhibit significant performance gains across
tasks such as instruction following, general knowledge, mathematics, and
coding. As illustrated in Figure 1, using Llama-3.1-8B-Instruct as the target
model, our fusion approach achieves an average improvement of 6.8 points across
14 benchmarks. Moreover, it demonstrates remarkable gains of 37.1 points and
30.1 points on the instruction-following benchmarks AlpacaEval-2 and
Arena-Hard, respectively. Our code, models, and datasets are available at
https://github.com/SLIT-AI/FuseChat-3.0.
