---
layout: publication
title: 'Debate On Graph: A Flexible And Reliable Reasoning Framework For Large Language Models'
authors: Jie Ma, Zhitao Gao, Qi Chai, Wangchun Sun, Pinghui Wang, Hongbin Pei, Jing Tao, Lingyun Song, Jun Liu, Chen Zhang, Lizhen Cui
conference: "Arxiv"
year: 2024
bibkey: ma2024debate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.03155'}
  - {name: "Code", url: 'https://github.com/reml-group/DoG'}
tags: ['Has Code', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) may suffer from hallucinations in real-world
applications due to the lack of relevant knowledge. In contrast, knowledge
graphs encompass extensive, multi-relational structures that store a vast array
of symbolic facts. Consequently, integrating LLMs with knowledge graphs has
been extensively explored, with Knowledge Graph Question Answering (KGQA)
serving as a critical touchstone for the integration. This task requires LLMs
to answer natural language questions by retrieving relevant triples from
knowledge graphs. However, existing methods face two significant challenges:
\textit\{excessively long reasoning paths distracting from the answer
generation\}, and \textit\{false-positive relations hindering the path
refinement\}. In this paper, we propose an iterative interactive KGQA framework
that leverages the interactive learning capabilities of LLMs to perform
reasoning and Debating over Graphs (DoG). Specifically, DoG employs a
subgraph-focusing mechanism, allowing LLMs to perform answer trying after each
reasoning step, thereby mitigating the impact of lengthy reasoning paths. On
the other hand, DoG utilizes a multi-role debate team to gradually simplify
complex questions, reducing the influence of false-positive relations. This
debate mechanism ensures the reliability of the reasoning process. Experimental
results on five public datasets demonstrate the effectiveness and superiority
of our architecture. Notably, DoG outperforms the state-of-the-art method ToG
by 23.7% and 9.1% in accuracy on WebQuestions and GrailQA, respectively.
Furthermore, the integration experiments with various LLMs on the mentioned
datasets highlight the flexibility of DoG. Code is available at
\url\{https://github.com/reml-group/DoG\}.
