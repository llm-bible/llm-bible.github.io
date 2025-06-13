---
layout: publication
title: 'Compressing Llms: The Truth Is Rarely Pure And Never Simple'
authors: Ajay Jaiswal, Zhe Gan, Xianzhi Du, Bowen Zhang, Zhangyang Wang, Yinfei Yang
conference: "Arxiv"
year: 2023
bibkey: jaiswal2023compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01382"}
  - {name: "Code", url: "https://github.com/VITA-Group/llm-kick"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pruning', 'Quantization', 'Has Code', 'Applications']
---
Despite their remarkable achievements, modern Large Language Models (LLMs)
face exorbitant computational and memory footprints. Recently, several works
have shown significant success in training-free and data-free compression
(pruning and quantization) of LLMs that achieve 50 - 60% sparsity and reduce
the bit width to 3 or 4 bits per weight, with negligible degradation of
perplexity over the uncompressed baseline. As recent research efforts are
focused on developing increasingly sophisticated compression methods, our work
takes a step back and re-evaluates the effectiveness of existing SoTA
compression methods, which rely on a fairly simple and widely questioned
metric, perplexity (even for dense LLMs). We introduce Knowledge-Intensive
Compressed LLM BenchmarK (LLM-KICK), a collection of carefully curated tasks to
redefine the evaluation protocol for compressed LLMs, which have significant
alignment with their dense counterparts and perplexity fail to capture subtle
change in their true capabilities. LLM-KICK unveils many favorable merits and
unfortunate plights of current SoTA compression methods: all pruning methods
suffer significant performance degradation, sometimes at trivial sparsity
ratios (e.g., 25-30%), and fail for N:M sparsity in knowledge-intensive tasks;
current quantization methods are more successful than pruning; yet, pruned LLMs
even at \\(\geq 50\\)% sparsity are robust in-context retrieval and summarization
systems; among others. LLM-KICK is designed to holistically access compressed
LLMs' ability for language understanding, reasoning, generation, in-context
retrieval, in-context summarization, etc. We hope our study can foster the
development of better LLM compression methods. The reproduced codes are
available at https://github.com/VITA-Group/llm-kick.
