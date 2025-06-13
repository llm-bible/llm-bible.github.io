---
layout: publication
title: 'Generalizing From Short To Long: Effective Data Synthesis For Long-context Instruction Tuning'
authors: Wenhao Zhu, Pinzhen Chen, Hanxu Hu, Shujian Huang, Fei Yuan, Jiajun Chen, Alexandra Birch
conference: "Arxiv"
year: 2025
bibkey: zhu2025generalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15592"}
  - {name: "Code", url: "https://github.com/NJUNLP/context-synthesis"}
tags: ['Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Long-context modelling for large language models (LLMs) has been a key area
of recent research because many real world use cases require reasoning over
longer inputs such as documents. The focus of research into modelling long
context has been on how to model position and there has been little
investigation into other important aspects of language modelling such as
instruction tuning. Long context training examples are challenging and
expensive to create and use. In this paper, we investigate how to design
instruction data for the post-training phase of a long context pre-trained
model: how much and what type of context is needed for optimal and efficient
post-training. Our controlled study reveals that models instruction-tuned on
short contexts can effectively generalize to longer ones, while also
identifying other critical factors such as instruction difficulty and context
composition. Based on these findings, we propose context synthesis, a novel
data synthesis framework that leverages off-the-shelf LLMs to generate extended
background contexts for high-quality instruction-answer pairs. Experiment
results on the document-level benchmark (LongBench) demonstrate that our
proposed approach outperforms previous instruction synthesis approaches and
comes close to the performance of human-annotated long-context instruction
data. The project will be available at:
https://github.com/NJUNLP/context-synthesis.
