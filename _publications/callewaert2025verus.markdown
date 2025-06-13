---
layout: publication
title: 'VERUS-LM: A Versatile Framework For Combining Llms With Symbolic Reasoning'
authors: Benjamin Callewaert, Simon Vandevelde, Joost Vennekens
conference: "Arxiv"
year: 2025
bibkey: callewaert2025verus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14540"}
tags: ['Tools', 'Efficiency and Optimization', 'Prompting', 'Reinforcement Learning']
---
A recent approach to neurosymbolic reasoning is to explicitly combine the
strengths of large language models (LLMs) and symbolic solvers to tackle
complex reasoning tasks. However, current approaches face significant
limitations, including poor generalizability due to task-specific prompts,
inefficiencies caused by the lack of separation between knowledge and queries,
and restricted inferential capabilities. These shortcomings hinder their
scalability and applicability across diverse domains. In this paper, we
introduce VERUS-LM, a novel framework designed to address these challenges.
VERUS-LM employs a generic prompting mechanism, clearly separates domain
knowledge from queries, and supports a wide range of different logical
reasoning tasks. This framework enhances adaptability, reduces computational
cost, and allows for richer forms of reasoning, such as optimization and
constraint satisfaction. We show that our approach succeeds in diverse
reasoning on a novel dataset, markedly outperforming LLMs. Additionally, our
system achieves competitive results on common reasoning benchmarks when
compared to other state-of-the-art approaches, and significantly surpasses them
on the difficult AR-LSAT dataset. By pushing the boundaries of hybrid
reasoning, VERUS-LM represents a significant step towards more versatile
neurosymbolic AI systems
