---
layout: publication
title: 'Reformatted Alignment'
authors: Run-ze Fan, Xuefeng Li, Haoyang Zou, Junlong Li, Shwai He, Ethan Chern, Jiewen Hu, Pengfei Liu
conference: "Arxiv"
year: 2024
bibkey: fan2024reformatted
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.12219'}
  - {name: "Code", url: 'https://github.com/GAIR-NLP/ReAlign'}
tags: ['Has Code', 'Interpretability and Explainability', 'RAG', 'Training Techniques', 'Reinforcement Learning']
---
The quality of finetuning data is crucial for aligning large language models
(LLMs) with human values. Current methods to improve data quality are either
labor-intensive or prone to factual errors caused by LLM hallucinations. This
paper explores elevating the quality of existing instruction data to better
align with human values, introducing a simple and effective approach named
ReAlign, which reformats the responses of instruction data into a format that
better aligns with pre-established criteria and the collated evidence. This
approach minimizes human annotation, hallucination, and the difficulty in
scaling, remaining orthogonal to existing alignment techniques. Experimentally,
ReAlign significantly boosts the general alignment ability, math reasoning,
factuality, and readability of the LLMs.
  Encouragingly, without introducing any additional data or advanced training
techniques, and merely by reformatting the response, LLaMA-2-13B's mathematical
reasoning ability on GSM8K can be improved from 46.77% to 56.63% in accuracy.
Additionally, a mere 5% of ReAlign data yields a 67% boost in general alignment
ability measured by the Alpaca dataset. This work highlights the need for
further research into the science and mechanistic interpretability of LLMs. We
have made the associated code and data publicly accessible to support future
studies at https://github.com/GAIR-NLP/ReAlign.
