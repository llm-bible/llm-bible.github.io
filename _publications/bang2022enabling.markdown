---
layout: publication
title: 'Enabling Classifiers To Make Judgements Explicitly Aligned With Human Values'
authors: Yejin Bang, Tiezheng Yu, Andrea Madotto, Zhaojiang Lin, Mona Diab, Pascale Fung
conference: "Arxiv"
year: 2022
bibkey: bang2022enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.07652"}
tags: ['Training Techniques', 'Few-Shot', 'Tools', 'Interpretability', 'Interpretability and Explainability', 'Prompting']
---
Many NLP classification tasks, such as sexism/racism detection or toxicity
detection, are based on human values. Yet, human values can vary under diverse
cultural conditions. Therefore, we introduce a framework for value-aligned
classification that performs prediction based on explicitly written human
values in the command. Along with the task, we propose a practical approach
that distills value-aligned knowledge from large-scale language models (LLMs)
to construct value-aligned classifiers in two steps. First, we generate
value-aligned training data from LLMs by prompt-based few-shot learning. Next,
we fine-tune smaller classification models with the generated data for the
task. Empirical results show that our VA-Models surpass multiple baselines by
at least 15.56% on the F1-score, including few-shot learning with OPT-175B and
existing text augmentation methods. We suggest that using classifiers with
explicit human value input improves both inclusivity & explainability in AI.
