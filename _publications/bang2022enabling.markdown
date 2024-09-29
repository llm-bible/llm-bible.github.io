---
layout: publication
title: Enabling Classifiers To Make Judgements Explicitly Aligned With Human Values
authors: Bang Yejin, Yu Tiezheng, Madotto Andrea, Lin Zhaojiang, Diab Mona, Fung Pascale
conference: "Arxiv"
year: 2022
bibkey: bang2022enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.07652"}
tags: ['Interpretability And Explainability', 'Prompting', 'Tools', 'Training Techniques']
---
Many NLP classification tasks such as sexism/racism detection or toxicity detection are based on human values. Yet human values can vary under diverse cultural conditions. Therefore we introduce a framework for value45;aligned classification that performs prediction based on explicitly written human values in the command. Along with the task we propose a practical approach that distills value45;aligned knowledge from large45;scale language models (LLMs) to construct value45;aligned classifiers in two steps. First we generate value45;aligned training data from LLMs by prompt45;based few45;shot learning. Next we fine45;tune smaller classification models with the generated data for the task. Empirical results show that our VA45;Models surpass multiple baselines by at least 15.5637; on the F145;score including few45;shot learning with OPT45;175B and existing text augmentation methods. We suggest that using classifiers with explicit human value input improves both inclusivity amp; explainability in AI.
