---
layout: publication
title: 'Outline, Then Details: Syntactically Guided Coarse-to-fine Code Generation'
authors: Wenqing Zheng, S P Sharan, Ajay Kumar Jaiswal, Kevin Wang, Yihan Xi, Dejia Xu, Zhangyang Wang
conference: "Arxiv"
year: 2023
bibkey: zheng2023then
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.00909"}
  - {name: "Code", url: "https://github.com/VITA-Group/ChainCoder"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Has Code', 'Pretraining Methods', 'Prompting']
---
For a complicated algorithm, its implementation by a human programmer usually
starts with outlining a rough control flow followed by iterative enrichments,
eventually yielding carefully generated syntactic structures and variables in a
hierarchy. However, state-of-the-art large language models generate codes in a
single pass, without intermediate warm-ups to reflect the structured thought
process of "outline-then-detail". Inspired by the recent success of
chain-of-thought prompting, we propose ChainCoder, a program synthesis language
model that generates Python code progressively, i.e. from coarse to fine in
multiple passes. We first decompose source code into layout frame components
and accessory components via abstract syntax tree parsing to construct a
hierarchical representation. We then reform our prediction target into a
multi-pass objective, each pass generates a subsequence, which is concatenated
in the hierarchy. Finally, a tailored transformer architecture is leveraged to
jointly encode the natural language descriptions and syntactically aligned I/O
data samples. Extensive evaluations show that ChainCoder outperforms
state-of-the-arts, demonstrating that our progressive generation eases the
reasoning procedure and guides the language model to generate higher-quality
solutions. Our codes are available at:
https://github.com/VITA-Group/ChainCoder.
