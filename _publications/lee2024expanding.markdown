---
layout: publication
title: 'Expanding Search Space With Diverse Prompting Agents: An Efficient Sampling Approach For LLM Mathematical Reasoning'
authors: Gisang Lee, Sangwoo Park, Junyoung Park, Andrew Chung, Sieun Park, Yoonah Park, Byungju Kim, Min-gyu Cho
conference: "Arxiv"
year: 2024
bibkey: lee2024expanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09780"}
tags: ['Fine-Tuning', 'RAG', 'Agentic', 'Prompting']
---
Large Language Models (LLMs) have exhibited remarkable capabilities in many
complex tasks including mathematical reasoning. However, traditional approaches
heavily rely on ensuring self-consistency within single prompting method, which
limits the exploration of diverse problem-solving strategies. This study
addresses these limitations by performing an experimental analysis of distinct
prompting methods within the domain of mathematical reasoning. Our findings
demonstrate that each method explores a distinct search space, and this
differentiation becomes more evident with increasing problem complexity. To
leverage this phenomenon, we applied efficient sampling process that uniformly
combines samples from these diverse methods, which not only expands the maximum
search space but achieves higher performance with fewer runs compared to single
methods. Especially, within the subset of difficult questions of MATH dataset
named MATH-hard, The maximum search space was achieved while utilizing
approximately 43% fewer runs than single methods on average. These findings
highlight the importance of integrating diverse problem-solving strategies to
enhance the reasoning abilities of LLMs.
