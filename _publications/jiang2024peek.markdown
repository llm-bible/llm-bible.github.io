---
layout: publication
title: 'A Peek Into Token Bias: Large Language Models Are Not Yet Genuine Reasoners'
authors: Bowen Jiang, Yangxinyu Xie, Zhuoqun Hao, Xiaomeng Wang, Tanwi Mallick, Weijie J. Su, Camillo J. Taylor, Dan Roth
conference: "Arxiv"
year: 2024
bibkey: jiang2024peek
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11050"}
  - {name: "Code", url: "https://github.com/bowen-upenn/llm_token_bias"}
tags: ['Ethics and Bias', 'Has Code', 'Tools']
---
This study introduces a hypothesis-testing framework to assess whether large
language models (LLMs) possess genuine reasoning abilities or primarily depend
on token bias. We go beyond evaluating LLMs on accuracy; rather, we aim to
investigate their token bias in solving logical reasoning tasks. Specifically,
we develop carefully controlled synthetic datasets, featuring conjunction
fallacy and syllogistic problems. Our framework outlines a list of hypotheses
where token biases are readily identifiable, with all null hypotheses assuming
genuine reasoning capabilities of LLMs. The findings in this study suggest,
with statistical guarantee, that most LLMs still struggle with logical
reasoning. While they may perform well on classic problems, their success
largely depends on recognizing superficial patterns with strong token bias,
thereby raising concerns about their actual reasoning and generalization
abilities. Codes and data are open-sourced at
https://github.com/bowen-upenn/llm_token_bias.
