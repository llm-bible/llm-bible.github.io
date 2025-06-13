---
layout: publication
title: 'Enhancing LLM Character-level Manipulation Via Divide And Conquer'
authors: Zhen Xiong, Yujun Cai, Bryan Hooi, Nanyun Peng, Zhecheng Li, Yiwei Wang
conference: "Arxiv"
year: 2025
bibkey: xiong2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08180"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Tokenization']
---
Large Language Models (LLMs) have demonstrated strong generalization
capabilities across a wide range of natural language processing (NLP) tasks.
However, they exhibit notable weaknesses in character-level string
manipulation, struggling with fundamental operations such as character
deletion, insertion, and substitution. These challenges stem primarily from
tokenization constraints, despite the critical role of such operations in data
preprocessing and code generation. Through systematic analysis, we derive two
key insights: (1) LLMs face significant difficulties in leveraging intrinsic
token knowledge for character-level reasoning, and (2) atomized word structures
can substantially enhance LLMs' ability to process token-level structural
information. Building on these insights, we propose Character-Level
Manipulation via Divide and Conquer, a novel approach designed to bridge the
gap between token-level processing and character-level manipulation. Our method
decomposes complex operations into explicit character-level subtasks coupled
with controlled token reconstruction phases, leading to significant
improvements in accuracy. Without additional training, our method significantly
improves accuracies on the \\(\texttt\{Deletion\}\\), \\(\texttt\{Insertion\}\\), and
\\(\texttt\{Substitution\}\\) tasks. To support further research, we open-source our
implementation and benchmarks.
