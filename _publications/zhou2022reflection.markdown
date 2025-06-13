---
layout: publication
title: 'Reflection Of Thought: Inversely Eliciting Numerical Reasoning In Language Models Via Solving Linear Systems'
authors: Fan Zhou, Haoyu Dong, Qian Liu, Zhoujun Cheng, Shi Han, Dongmei Zhang
conference: "Arxiv"
year: 2022
bibkey: zhou2022reflection
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.05075'}
tags: ['Few-Shot', 'RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Numerical reasoning over natural language has been a long-standing goal for
the research community. However, cutting-edge language models have proven
difficult to reliably generalize to a broad range of numbers, although they
have shown proficiency in reasoning over common and simple numbers. In this
paper, we propose a novel method to elicit and exploit the numerical reasoning
knowledge hidden in pre-trained language models using simple anchor numbers.
Concretely, we first leverage simple numbers as anchors to probe the implicitly
inferred arithmetic expressions from language models, and then explicitly apply
the expressions on complex numbers to get corresponding answers. To inversely
elicit arithmetic expressions, we transform and formulate the task as an
analytically solvable linear system. Experimental results on several numerical
reasoning benchmarks demonstrate that our approach significantly improves
numerical reasoning capabilities of existing LMs. More importantly, our
approach is training-free and simply works in the inference phase, making it
highly portable and achieving consistent performance benefits across a variety
of language models (GPT-3, T5, BART, etc) in all zero-shot, few-shot, and
fine-tuning scenarios.
