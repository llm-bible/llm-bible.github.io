---
layout: publication
title: 'Parse Trees Guided LLM Prompt Compression'
authors: Wenhao Mao, Chengbin Hou, Tianyu Zhang, Xinyu Lin, Ke Tang, Hairong Lv
conference: "Arxiv"
year: 2024
bibkey: mao2024parse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15395"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning']
---
Offering rich contexts to Large Language Models (LLMs) has shown to boost the
performance in various tasks, but the resulting longer prompt would increase
the computational cost and might exceed the input limit of LLMs. Recently, some
prompt compression methods have been suggested to shorten the length of prompts
by using language models to generate shorter prompts or by developing
computational models to select important parts of original prompt. The
generative compression methods would suffer from issues like hallucination,
while the selective compression methods have not involved linguistic rules and
overlook the global structure of prompt. To this end, we propose a novel
selective compression method called PartPrompt. It first obtains a parse tree
for each sentence based on linguistic rules, and calculates local information
entropy for each node in a parse tree. These local parse trees are then
organized into a global tree according to the hierarchical structure such as
the dependency of sentences, paragraphs, and sections. After that, the
root-ward propagation and leaf-ward propagation are proposed to adjust node
values over the global tree. Finally, a recursive algorithm is developed to
prune the global tree based on the adjusted node values. The experiments show
that PartPrompt receives the state-of-the-art performance across various
datasets, metrics, compression ratios, and target LLMs for inference. The
in-depth ablation studies confirm the effectiveness of designs in PartPrompt,
and other additional experiments also demonstrate its superiority in terms of
the coherence of compressed prompts and in the extreme long prompt scenario.
