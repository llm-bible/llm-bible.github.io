---
layout: publication
title: 'Are Pretrained Transformers Robust In Intent Classification? A Missing Ingredient In Evaluation Of Out-of-scope Intent Detection'
authors: Jianguo Zhang, Kazuma Hashimoto, Yao Wan, Zhiwei Liu, Ye Liu, Caiming Xiong, Philip S. Yu
conference: "Arxiv"
year: 2021
bibkey: zhang2021are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.04564"}
  - {name: "Code", url: "https://github.com/jianguoz/Few-Shot-Intent-Detection"}
tags: ['Security', 'Model Architecture', 'Few-Shot', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Pre-trained Transformer-based models were reported to be robust in intent
classification. In this work, we first point out the importance of in-domain
out-of-scope detection in few-shot intent recognition tasks and then illustrate
the vulnerability of pre-trained Transformer-based models against samples that
are in-domain but out-of-scope (ID-OOS). We construct two new datasets, and
empirically show that pre-trained models do not perform well on both ID-OOS
examples and general out-of-scope examples, especially on fine-grained few-shot
intent detection tasks. To figure out how the models mistakenly classify ID-OOS
intents as in-scope intents, we further conduct analysis on confidence scores
and the overlapping keywords, as well as point out several prospective
directions for future work. Resources are available on
https://github.com/jianguoz/Few-Shot-Intent-Detection.
