---
layout: publication
title: 'Neurogen: Neural Network Parameter Generation Via Large Language Models'
authors: Jiaqi Wang, Yusen Zhang, Xi Li
conference: "Arxiv"
year: 2025
bibkey: wang2025neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12470"}
tags: ['Prompting', 'Efficiency and Optimization', 'Model Architecture']
---
Acquiring the parameters of neural networks (NNs) has been one of the most important problems in machine learning since the inception of NNs. Traditional approaches, such as backpropagation and forward-only optimization, acquire parameters via iterative data fitting to gradually optimize them. This paper aims to explore the feasibility of a new direction: acquiring NN parameters via large language model generation. We propose NeuroGen, a generalized and easy-to-implement two-stage approach for NN parameter generation conditioned on descriptions of the data, task, and network architecture. Stage one is Parameter Reference Knowledge Injection, where LLMs are pretrained on NN checkpoints to build foundational understanding of parameter space, whereas stage two is Context-Enhanced Instruction Tuning, enabling LLMs to adapt to specific tasks through enriched, task-aware prompts. Experimental results demonstrate that NeuroGen effectively generates usable NN parameters. Our findings highlight the feasibility of LLM-based NN parameter generation and suggest a promising new paradigm where LLMs and lightweight NNs can coexist synergistically
