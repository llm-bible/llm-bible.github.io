---
layout: publication
title: 'Analyzing Memorization In Large Language Models Through The Lens Of Model Attribution'
authors: Tarun Ram Menta, Susmit Agrawal, Chirag Agarwal
conference: "Arxiv"
year: 2025
bibkey: menta2025analyzing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.05078'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) are prevalent in modern applications but often
memorize training data, leading to privacy breaches and copyright issues.
Existing research has mainly focused on posthoc analyses, such as extracting
memorized content or developing memorization metrics, without exploring the
underlying architectural factors that contribute to memorization. In this work,
we investigate memorization from an architectural lens by analyzing how
attention modules at different layers impact its memorization and
generalization performance. Using attribution techniques, we systematically
intervene in the LLM architecture by bypassing attention modules at specific
blocks while keeping other components like layer normalization and MLP
transformations intact. We provide theorems analyzing our intervention
mechanism from a mathematical view, bounding the difference in layer outputs
with and without our attributions. Our theoretical and empirical analyses
reveal that attention modules in deeper transformer blocks are primarily
responsible for memorization, whereas earlier blocks are crucial for the models
generalization and reasoning capabilities. We validate our findings through
comprehensive experiments on different LLM families (Pythia and GPTNeo) and
five benchmark datasets. Our insights offer a practical approach to mitigate
memorization in LLMs while preserving their performance, contributing to safer
and more ethical deployment in real world applications.
