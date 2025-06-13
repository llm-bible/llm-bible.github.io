---
layout: publication
title: 'NSA: Neuro-symbolic ARC Challenge'
authors: Paweł Batorski, Jannik Brinkmann, Paul Swoboda
conference: "Arxiv"
year: 2025
bibkey: batorski2025neuro
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04424"}
  - {name: "Code", url: "https://github.com/Batorskq/NSA"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Has Code']
---
The Abstraction and Reasoning Corpus (ARC) evaluates general reasoning
capabilities that are difficult for both machine learning models and
combinatorial search methods. We propose a neuro-symbolic approach that
combines a transformer for proposal generation with combinatorial search using
a domain-specific language. The transformer narrows the search space by
proposing promising search directions, which allows the combinatorial search to
find the actual solution in short time. We pre-train the trainsformer with
synthetically generated data. During test-time we generate additional
task-specific training tasks and fine-tune our model. Our results surpass
comparable state of the art on the ARC evaluation set by 27% and compare
favourably on the ARC train set. We make our code and dataset publicly
available at https://github.com/Batorskq/NSA.
