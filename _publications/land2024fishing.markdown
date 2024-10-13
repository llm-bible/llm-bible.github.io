---
layout: publication
title: 'Fishing For Magikarp: Automatically Detecting Under-trained Tokens In Large Language Models'
authors: Land Sander, Bartolo Max
conference: "Arxiv"
year: 2024
bibkey: land2024fishing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05417"}
tags: ['Efficiency And Optimization', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques', 'Uncategorized']
---
The disconnect between tokenizer creation and model training in language
models has been known to allow for certain inputs, such as the infamous
SolidGoldMagikarp token, to induce unwanted behaviour. Although such `glitch
tokens' that are present in the tokenizer vocabulary, but are nearly or fully
absent in training, have been observed across a variety of different models, a
consistent way of identifying them has been missing. We present a comprehensive
analysis of Large Language Model (LLM) tokenizers, specifically targeting this
issue of detecting untrained and under-trained tokens. Through a combination of
tokenizer analysis, model weight-based indicators, and prompting techniques, we
develop effective methods for automatically detecting these problematic tokens.
Our findings demonstrate the prevalence of such tokens across various models
and provide insights into improving the efficiency and safety of language
models.
