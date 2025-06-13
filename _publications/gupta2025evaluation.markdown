---
layout: publication
title: 'WHODUNIT: Evaluation Benchmark For Culprit Detection In Mystery Stories'
authors: Kshitij Gupta
conference: "Arxiv"
year: 2025
bibkey: gupta2025evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07747"}
tags: ['Security', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Prompting']
---
We present a novel data set, WhoDunIt, to assess the deductive reasoning
capabilities of large language models (LLM) within narrative contexts.
Constructed from open domain mystery novels and short stories, the dataset
challenges LLMs to identify the perpetrator after reading and comprehending the
story. To evaluate model robustness, we apply a range of character-level name
augmentations, including original names, name swaps, and substitutions with
well-known real and/or fictional entities from popular discourse. We further
use various prompting styles to investigate the influence of prompting on
deductive reasoning accuracy.
  We conduct evaluation study with state-of-the-art models, specifically
GPT-4o, GPT-4-turbo, and GPT-4o-mini, evaluated through multiple trials with
majority response selection to ensure reliability. The results demonstrate that
while LLMs perform reliably on unaltered texts, accuracy diminishes with
certain name substitutions, particularly those with wide recognition. This
dataset is publicly available here.
