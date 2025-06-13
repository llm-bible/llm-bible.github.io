---
layout: publication
title: 'GRP: Goal-reversed Prompting For Zero-shot Evaluation With Llms'
authors: Mingyang Song, Mao Zheng, Xuan Luo
conference: "Arxiv"
year: 2025
bibkey: song2025goal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06139"}
tags: ['RAG', 'Prompting']
---
Using Large Language Models (LLMs) to evaluate and compare two answers from
different models typically involves having LLM-based judges select the better
answer. However, humans often approach problem-solving from a reverse
perspective, for instance, by choosing the worse option instead of the better
one in a pairwise comparison. Generally, this kind of reverse thinking plays a
crucial role in human reasoning and decision-making and can further test the
difference between original and reverse thought processes simultaneously. To
address the above issue, in this paper, we propose a Goal-Reversed Prompting
(GRP) approach for pairwise evaluation that shifts the original task from
selecting the better answer to choosing the worse one. We encourage LLMs to
think in reverse by prompting LLMs to identify the worse response. Experiments
on closed-source models demonstrate that GRP significantly enhances evaluation
capabilities, outperforming the prompt template with the original goal.
