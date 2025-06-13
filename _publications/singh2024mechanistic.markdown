---
layout: publication
title: 'Mechanistic Behavior Editing Of Language Models'
authors: Joykirat Singh, Subhabrata Dutta, Tanmoy Chakraborty
conference: "Arxiv"
year: 2024
bibkey: singh2024mechanistic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04277'}
  - {name: "Code", url: 'https://github.com/joykirat18/TaRot'}
tags: ['Has Code', 'Few-Shot', 'RAG', 'Efficiency and Optimization', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Large Language Models trained on web-scale text acquire language generation
abilities that can solve a wide range of tasks, particularly when task
knowledge is refined into the generative prior using in-context examples.
However, spurious features learned from noisy data hinder their
generalizability. Supervised finetuning can introduce task specificity, but
introduce data inefficiency. Prior studies indicate that (i) noisy neural
circuitries coexist with generalizable ones within LLMs, and (ii) finetuning
typically enhances (or suppresses) existing abilities without introducing newer
ones. Building upon these, we propose TaRot, a novel method for task
adaptation. TaRot intervenes in the neural circuitries using learnable rotation
matrices that are optimized using Bayesian Optimization, on labelled samples in
the order of standard few-shot prompting examples. Experiments on multiple
classification and generation tasks using LLMs of varying sizes reveal the
efficacy of TaRot, improving upon both zero- as well as few-shot performance,
with average improvements (across models and tasks) of 23.81% and 11.15%,
respectively. The source code is available at
https://github.com/joykirat18/TaRot
