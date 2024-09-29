---
layout: publication
title: "Compact Language Models Via Pruning And Knowledge Distillation"
authors: Muralidharan Saurav, Sreenivas Sharath Turuvekere, Joshi Raviraj, Chochowski Marcin, Patwary Mostofa, Shoeybi Mohammad, Catanzaro Bryan, Kautz Jan, Molchanov Pavlo
conference: "Arxiv"
year: 2024
bibkey: muralidharan2024compact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14679"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'Pruning', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) targeting different deployment scales and sizes are currently produced by training each variant from scratch; this is extremely compute-intensive. In this paper we investigate if pruning an existing LLM and then re-training it with a fraction (<337;) of the original training data can be a suitable alternative to repeated full retraining. To this end we develop a set of practical and effective compression best practices for LLMs that combine depth width attention and MLP pruning with knowledge distillation-based retraining; we arrive at these best practices through a detailed empirical exploration of pruning strategies for each axis methods to combine axes distillation strategies and search techniques for arriving at optimal compressed architectures. We use this guide to compress the Nemotron-4 family of LLMs by a factor of 2-4x and compare their performance to similarly-sized models on a variety of language modeling tasks. Deriving 8B and 4B models from an already pretrained 15B model using our approach requires up to 40x fewer training tokens per model compared to training from scratch; this results in compute cost savings of 1.8x for training the full model family (15B 8B and 4B). Minitron models exhibit up to a 1637; improvement in MMLU scores compared to training from scratch perform comparably to other community models such as Mistral 7B Gemma 7B and Llama-3 8B and outperform state-of-the-art compression techniques from the literature. We have open-sourced Minitron model weights on Huggingface with corresponding supplementary material including example code available on GitHub.
