---
layout: publication
title: Novel-wd: Exploring Acquisition Of Novel World Knowledge In Llms Using Prefix-tuning
authors: Méloux Maxime, Cerisara Christophe
conference: "Arxiv"
year: 2024
bibkey: méloux2024novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.17070"}
tags: ['Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Teaching new information to pre-trained large language models (PLM) is a crucial but challenging task. Model adaptation techniques such as fine-tuning and parameter-efficient training have been shown to store new facts at a slow rate; continual learning is an option but is costly and prone to catastrophic forgetting. This work studies and quantifies how PLM may learn and remember new world knowledge facts that do not occur in their pre-training corpus which only contains world knowledge up to a certain date. To that purpose we first propose Novel-WD a new dataset consisting of sentences containing novel facts extracted from recent Wikidata updates along with two evaluation tasks in the form of causal language modeling and multiple choice questions (MCQ). We make this dataset freely available to the community and release a procedure to later build new versions of similar datasets with up-to-date information. We also explore the use of prefix-tuning for novel information learning and analyze how much information can be stored within a given prefix. We show that a single fact can reliably be encoded within a single prefix and that the prefix capacity increases with its length and with the base model size.
