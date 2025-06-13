---
layout: publication
title: 'Musegraph: Graph-oriented Instruction Tuning Of Large Language Models For Generic Graph Mining'
authors: Yanchao Tan, Hang Lv, Xinyi Huang, Jiawei Zhang, Shiping Wang, Carl Yang
conference: "Arxiv"
year: 2024
bibkey: tan2024graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.04780'}
tags: ['GPT', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'Reinforcement Learning']
---
Graphs with abundant attributes are essential in modeling interconnected
entities and improving predictions in various real-world applications.
Traditional Graph Neural Networks (GNNs), which are commonly used for modeling
attributed graphs, need to be re-trained every time when applied to different
graph tasks and datasets. Although the emergence of Large Language Models
(LLMs) has introduced a new paradigm in natural language processing, the
generative potential of LLMs in graph mining remains largely under-explored. To
this end, we propose a novel framework MuseGraph, which seamlessly integrates
the strengths of GNNs and LLMs and facilitates a more effective and generic
approach for graph mining across different tasks and datasets. Specifically, we
first introduce a compact graph description via the proposed adaptive input
generation to encapsulate key information from the graph under the constraints
of language token limitations. Then, we propose a diverse instruction
generation mechanism, which distills the reasoning capabilities from LLMs
(e.g., GPT-4) to create task-specific Chain-of-Thought-based instruction
packages for different graph tasks. Finally, we propose a graph-aware
instruction tuning with a dynamic instruction package allocation strategy
across tasks and datasets, ensuring the effectiveness and generalization of the
training process. Our experimental results demonstrate significant improvements
in different graph tasks, showcasing the potential of our MuseGraph in
enhancing the accuracy of graph-oriented downstream tasks while keeping the
generation powers of LLMs.
