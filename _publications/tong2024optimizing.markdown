---
layout: publication
title: Optimizing Language Model's Reasoning Abilities With Weak Supervision
authors: Tong Yongqi, Wang Sizhe, Li Dawei, Wang Yifan, Han Simeng, Lin Zi, Huang Chengsong, Huang Jiaxin, Shang Jingbo
conference: "Arxiv"
year: 2024
bibkey: tong2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.04086"}
tags: ['Fine Tuning', 'Interpretability And Explainability', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
While Large Language Models (LLMs) have demonstrated proficiency in handling complex queries much of the past work has depended on extensively annotated datasets by human experts. However this reliance on fully-supervised annotations poses scalability challenges particularly as models and data requirements grow. To mitigate this we explore the potential of enhancing LLMs reasoning abilities with minimal human supervision. In this work we introduce self-reinforcement which begins with Supervised Fine-Tuning (SFT) of the model using a small collection of annotated questions. Then it iteratively improves LLMs by learning from the differences in responses from the SFT and unfinetuned models on unlabeled questions. Our approach provides an efficient approach without relying heavily on extensive human-annotated explanations. However current reasoning benchmarks typically only include golden-reference answers or rationales. Therefore we present (textscPuzzleBen) a weakly supervised benchmark that comprises 25147 complex questions answers and human-generated rationales across various domains such as brainteasers puzzles riddles parajumbles and critical reasoning tasks. A unique aspect of our dataset is the inclusion of 10000 unannotated questions enabling us to explore utilizing fewer supersized data to boost LLMs inference capabilities. Our experiments underscore the significance of (textscPuzzleBen) as well as the effectiveness of our methodology as a promising direction in future endeavors. Our dataset and code will be published soon on (texttt)Anonymity Link.
