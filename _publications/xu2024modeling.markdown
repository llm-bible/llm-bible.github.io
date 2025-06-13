---
layout: publication
title: 'Pathreasoner: Modeling Reasoning Path With Equivalent Extension For Logical Question Answering'
authors: Fangzhi Xu, Qika Lin, Tianzhe Zhao, Jiawei Han, Jun Liu
conference: "Arxiv"
year: 2024
bibkey: xu2024modeling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.19109'}
tags: ['Attention Mechanism', 'Transformer', 'GPT', 'Model Architecture', 'Merging', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Logical reasoning task has attracted great interest since it was proposed.
Faced with such a task, current competitive models, even large language models
(e.g., ChatGPT and PaLM 2), still perform badly. Previous promising LMs
struggle in logical consistency modeling and logical structure perception. To
this end, we model the logical reasoning task by transforming each logical
sample into reasoning paths and propose an architecture \textbf\{PathReasoner\}.
It addresses the task from the views of both data and model. To expand the
diversity of the logical samples, we propose an atom extension strategy
supported by equivalent logical formulas, to form new reasoning paths. From the
model perspective, we design a stack of transformer-style blocks. In
particular, we propose a path-attention module to joint model in-atom and
cross-atom relations with the high-order diffusion strategy. Experiments show
that PathReasoner achieves competitive performances on two logical reasoning
benchmarks and great generalization abilities.
