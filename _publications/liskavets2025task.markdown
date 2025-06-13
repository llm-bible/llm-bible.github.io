---
layout: publication
title: 'Task-agnostic Prompt Compression With Context-aware Sentence Embedding And Reward-guided Task Descriptor'
authors: Barys Liskavets, Shuvendu Roy, Maxim Ushakov, Mark Klibanov, Ali Etemad, Shane Luke
conference: "Arxiv"
year: 2025
bibkey: liskavets2025task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13374"}
tags: ['Prompting', 'Tools', 'Reinforcement Learning']
---
The rise of Large Language Models (LLMs) has led to significant interest in
prompt compression, a technique aimed at reducing the length of input prompts
while preserving critical information. However, the prominent approaches in
prompt compression often require explicit questions or handcrafted templates
for compression, limiting their generalizability. We propose Task-agnostic
Prompt Compression (TPC), a novel framework that generalizes compression across
tasks and domains without requiring input questions or templates. TPC generates
a context-relevant task description using a task descriptor trained on a
curated dataset of context and query pairs, and fine-tuned via reinforcement
learning with a reward function designed to capture the most relevant
information. The task descriptor is then utilized to compute the relevance of
each sentence in the prompt to generate the compressed prompt. We introduce 3
model sizes (Base, Large, and Huge), where the largest model outperforms the
existing state-of-the-art methods on LongBench and ZeroSCROLLS benchmarks, and
our smallest model performs comparable to the existing solutions while being
considerably smaller.
