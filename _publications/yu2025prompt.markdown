---
layout: publication
title: 'ICPC: In-context Prompt Compression With Faster Inference'
authors: Ziyang Yu, Yuyu Liu
conference: "Arxiv"
year: 2025
bibkey: yu2025prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01625"}
tags: ['Prompting']
---
Despite the recent success of Large Language Models (LLMs), it remains
challenging to feed LLMs with long prompts due to the fixed size of LLM inputs.
As a remedy, prompt compression becomes a promising solution by removing
redundant tokens in the prompt. However, using LLM in the existing works
requires additional computation resources and leads to memory overheads. To
address it, we propose ICPC (In-context Prompt Compression), a novel and
scalable prompt compression method that adaptively reduces the prompt length.
The key idea of ICPC is to calculate the probability of each word appearing in
the prompt using encoders and calculate information carried by each word
through the information function, which effectively reduces the information
loss during prompt compression and increases the speed of compression.
Empirically, we demonstrate that ICPC can effectively compress long texts of
different categories and thus achieve better performance and speed on different
types of NLP tasks.
