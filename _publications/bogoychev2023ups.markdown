---
layout: publication
title: 'The Ups And Downs Of Large Language Model Inference With Vocabulary Trimming By Language Heuristics'
authors: Bogoychev Nikolay, Chen Pinzhen, Haddow Barry, Birch Alexandra
conference: "Arxiv"
year: 2023
bibkey: bogoychev2023ups
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09709"}
tags: ['Applications', 'Efficiency And Optimization', 'Reinforcement Learning']
---
"Deploying large language models (LLMs) encounters challenges due to intensive computational and memory requirements. Our research examines vocabulary trimming (VT) inspired by restricting embedding entries to the language of interest to bolster time and memory efficiency. While such modifications have been proven effective in tasks like machine translation, tailoring them to LLMs demands specific modifications given the diverse nature of LLM applications. We apply two language heuristics to trim the full vocabulary - Unicode-based script filtering and corpus-based selection - to different LLM families and sizes. The methods are straightforward, interpretable, and easy to implement. It is found that VT reduces the memory usage of small models by nearly 50&#37; and has an upper bound of 25&#37; improvement in generation speed. Yet, we reveal the limitations of these methods in that they do not perform consistently well for each language with diminishing returns in larger models."
