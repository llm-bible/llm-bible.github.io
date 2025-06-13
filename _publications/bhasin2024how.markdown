---
layout: publication
title: 'How Does Multi-task Training Affect Transformer In-context Capabilities? Investigations With Function Classes'
authors: Harmon Bhasin, Timothy Ossowski, Yiqiao Zhong, Junjie Hu
conference: "Arxiv"
year: 2024
bibkey: bhasin2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03558"}
  - {name: "Code", url: "https://github.com/harmonbhasin/curriculum_learning_icl"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large language models (LLM) have recently shown the extraordinary ability to
perform unseen tasks based on few-shot examples provided as text, also known as
in-context learning (ICL). While recent works have attempted to understand the
mechanisms driving ICL, few have explored training strategies that incentivize
these models to generalize to multiple tasks. Multi-task learning (MTL) for
generalist models is a promising direction that offers transfer learning
potential, enabling large parameterized models to be trained from simpler,
related tasks. In this work, we investigate the combination of MTL with ICL to
build models that efficiently learn tasks while being robust to
out-of-distribution examples. We propose several effective curriculum learning
strategies that allow ICL models to achieve higher data efficiency and more
stable convergence. Our experiments reveal that ICL models can effectively
learn difficult tasks by training on progressively harder tasks while mixing in
prior tasks, denoted as mixed curriculum in this work. Our code and models are
available at https://github.com/harmonbhasin/curriculum_learning_icl .
