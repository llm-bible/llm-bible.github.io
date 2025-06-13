---
layout: publication
title: 'Evaluate What You Can''t Evaluate: Unassessable Quality For Generated Response'
authors: Yongkang Liu, Shi Feng, Daling Wang, Yifei Zhang, Hinrich Schütze
conference: "Arxiv"
year: 2023
bibkey: liu2023evaluate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.14658'}
tags: ['GPT', 'Security', 'Model Architecture']
---
LLMs (large language models) such as ChatGPT have shown remarkable language
understanding and generation capabilities. Although reference-free evaluators
based on LLMs show better human alignment than traditional reference-based
evaluators, there are many challenges in using reference-free evaluators based
on LLMs. Reference-free evaluators are more suitable for open-ended examples
with different semantics responses. But not all examples are open-ended. For
closed-ended examples with unique correct semantic response, reference-free
evaluators will still consider it high quality when giving a response that is
inconsistent with the facts and the semantic of reference. In order to
comprehensively evaluate the reliability of evaluators based on LLMs, we
construct two adversarial meta-evaluation dialogue generation datasets
KdConv-ADV and DSTC7-ADV based on KdConv and DSTC7-AVSD, respectively. Compared
to previous meta-evaluation benchmarks, KdConv-ADV and DSTC7-ADV are much more
challenging since they requires evaluators to be able to reasonably evaluate
closed-ended examples with the help of external knowledge or even its own
knowledge. Empirical results show that the ability of LLMs to identify
unreasonable responses is insufficient. There are risks in using eference-free
evaluators based on LLMs to evaluate the quality of dialogue responses.
