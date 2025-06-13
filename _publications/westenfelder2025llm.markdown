---
layout: publication
title: 'Llm-supported Natural Language To Bash Translation'
authors: Finnian Westenfelder, Erik Hemberg, Miguel Tulla, Stephen Moskal, Una-may O'reilly, Silviu Chiricescu
conference: "Arxiv"
year: 2025
bibkey: westenfelder2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06858"}
  - {name: "Code", url: "https://github.com/westenfelder/NL2SH"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Has Code', 'Prompting', 'In-Context Learning']
---
The Bourne-Again Shell (Bash) command-line interface for Linux systems has
complex syntax and requires extensive specialized knowledge. Using the natural
language to Bash command (NL2SH) translation capabilities of large language
models (LLMs) for command composition circumvents these issues. However, the
NL2SH performance of LLMs is difficult to assess due to inaccurate test data
and unreliable heuristics for determining the functional equivalence of Bash
commands. We present a manually verified test dataset of 600
instruction-command pairs and a training dataset of 40,939 pairs, increasing
the size of previous datasets by 441% and 135%, respectively. Further, we
present a novel functional equivalence heuristic that combines command
execution with LLM evaluation of command outputs. Our heuristic can determine
the functional equivalence of two Bash commands with 95% confidence, a 16%
increase over previous heuristics. Evaluation of popular LLMs using our test
dataset and heuristic demonstrates that parsing, in-context learning, in-weight
learning, and constrained decoding can improve NL2SH accuracy by up to 32%. Our
findings emphasize the importance of dataset quality, execution-based
evaluation and translation method for advancing NL2SH translation. Our code is
available at https://github.com/westenfelder/NL2SH
