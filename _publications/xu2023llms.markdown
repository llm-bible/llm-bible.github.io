---
layout: publication
title: "Llms And The Abstraction And Reasoning Corpus: Successes, Failures, And The Importance Of Object-based Representations"
authors: Xu Yudong, Li Wenhao, Vaezipoor Pashootan, Sanner Scott, Khalil Elias B.
conference: "Arxiv"
year: 2023
bibkey: xu2023llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18354"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Can a Large Language Model (LLM) solve simple abstract reasoning problems We explore this broad question through a systematic analysis of GPT on the Abstraction and Reasoning Corpus (ARC) a representative benchmark of abstract reasoning ability from limited examples in which solutions require some core knowledge of concepts such as objects goal states counting and basic geometry. GPT-4 solves only 13/50 of the most straightforward ARC tasks when using textual encodings for their two-dimensional input-output grids. Our failure analysis reveals that GPT-4s capacity to identify objects and reason about them is significantly influenced by the sequential nature of the text that represents an object within a text encoding of a task. To test this hypothesis we design a new benchmark the 1D-ARC which consists of one-dimensional (array-like) tasks that are more conducive to GPT-based reasoning and where it indeed performs better than on the (2D) ARC. To alleviate this issue we propose an object-based representation that is obtained through an external tool resulting in nearly doubling the performance on solved ARC tasks and near-perfect scores on the easier 1D-ARC. Although the state-of-the-art GPT-4 is unable to reason perfectly within non-language domains such as the 1D-ARC or a simple ARC subset our study reveals that the use of object-based representations can significantly improve its reasoning ability. Visualizations GPT logs and data are available at https://khalil-research.github.io/LLM4ARC."
