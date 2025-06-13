---
layout: publication
title: 'Retrospective Learning From Interactions'
authors: Zizhao Chen, Mustafa Omer Gul, Yiwei Chen, Gloria Geng, Anne Wu, Yoav Artzi
conference: "Arxiv"
year: 2024
bibkey: chen2024retrospective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13852"}
tags: ['Multimodal Models']
---
Multi-turn interactions between large language models (LLMs) and users naturally include implicit feedback signals. If an LLM responds in an unexpected way to an instruction, the user is likely to signal it by rephrasing the request, expressing frustration, or pivoting to an alternative task. Such signals are task-independent and occupy a relatively constrained subspace of language, allowing the LLM to identify them even if it fails on the actual task. We introduce ReSpect, a method to learn from such signals in past interactions via retrospection without additional annotations. We deploy ReSpect in a new multimodal interaction scenario, where humans instruct a multimodal LLM to solve an abstract reasoning task with a combinatorial solution space. Through thousands of interactions with humans, we show how ReSpect gradually improves task completion rate from 31% to 82%, all without any external annotation.
