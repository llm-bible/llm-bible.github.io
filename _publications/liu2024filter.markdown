---
layout: publication
title: 'Filter-then-generate: Large Language Models With Structure-text Adapter For Knowledge Graph Completion'
authors: Ben Liu, Jihai Zhang, Fangquan Lin, Cheng Yang, Min Peng
conference: "Arxiv"
year: 2024
bibkey: liu2024filter
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.09094'}
  - {name: "Code", url: 'https://github.com/LB0828/FtG'}
tags: ['Fine-Tuning', 'Has Code', 'Prompting', 'Applications']
---
Large Language Models (LLMs) present massive inherent knowledge and superior
semantic comprehension capability, which have revolutionized various tasks in
natural language processing. Despite their success, a critical gap remains in
enabling LLMs to perform knowledge graph completion (KGC). Empirical evidence
suggests that LLMs consistently perform worse than conventional KGC approaches,
even through sophisticated prompt design or tailored instruction-tuning.
Fundamentally, applying LLMs on KGC introduces several critical challenges,
including a vast set of entity candidates, hallucination issue of LLMs, and
under-exploitation of the graph structure. To address these challenges, we
propose a novel instruction-tuning-based method, namely FtG. Specifically, we
present a filter-then-generate paradigm and formulate the KGC task into a
multiple-choice question format. In this way, we can harness the capability of
LLMs while mitigating the issue casused by hallucinations. Moreover, we devise
a flexible ego-graph serialization prompt and employ a structure-text adapter
to couple structure and text information in a contextualized manner.
Experimental results demonstrate that FtG achieves substantial performance gain
compared to existing state-of-the-art methods. The instruction dataset and code
are available at https://github.com/LB0828/FtG.
