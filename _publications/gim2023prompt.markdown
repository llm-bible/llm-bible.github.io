---
layout: publication
title: Prompt Cache Modular Attention Reuse For Low-latency Inference
authors: Gim In, Chen Guojun, Lee Seung-seob, Sarda Nikhil, Khandelwal Anurag, Zhong Lin
conference: "Arxiv"
year: 2023
bibkey: gim2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04934"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
We present Prompt Cache an approach for accelerating inference for large language models (LLM) by reusing attention states across different LLM prompts. Many input prompts have overlapping text segments such as system messages prompt templates and documents provided for context. Our key insight is that by precomputing and storing the attention states of these frequently occurring text segments on the inference server we can efficiently reuse them when these segments appear in user prompts. Prompt Cache employs a schema to explicitly define such reusable text segments called prompt modules. The schema ensures positional accuracy during attention state reuse and provides users with an interface to access cached states in their prompt. Using a prototype implementation we evaluate Prompt Cache across several LLMs. We show that Prompt Cache significantly reduce latency in time-to-first-token especially for longer prompts such as document-based question answering and recommendations. The improvements range from 8x for GPU-based inference to 60x for CPU-based inference all while maintaining output accuracy and without the need for model parameter modifications.
