---
layout: publication
title: Evaluate What You Cant Evaluate Unassessable Quality For Generated Response
authors: Liu Yongkang, Feng Shi, Wang Daling, Zhang Yifei, Schütze Hinrich
conference: "Arxiv"
year: 2023
bibkey: liu2023evaluate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14658"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Security']
---
LLMs (large language models) such as ChatGPT have shown remarkable language understanding and generation capabilities. Although reference45;free evaluators based on LLMs show better human alignment than traditional reference45;based evaluators there are many challenges in using reference45;free evaluators based on LLMs. Reference45;free evaluators are more suitable for open45;ended examples with different semantics responses. But not all examples are open45;ended. For closed45;ended examples with unique correct semantic response reference45;free evaluators will still consider it high quality when giving a response that is inconsistent with the facts and the semantic of reference. In order to comprehensively evaluate the reliability of evaluators based on LLMs we construct two adversarial meta45;evaluation dialogue generation datasets KdConv45;ADV and DSTC745;ADV based on KdConv and DSTC745;AVSD respectively. Compared to previous meta45;evaluation benchmarks KdConv45;ADV and DSTC745;ADV are much more challenging since they requires evaluators to be able to reasonably evaluate closed45;ended examples with the help of external knowledge or even its own knowledge. Empirical results show that the ability of LLMs to identify unreasonable responses is insufficient. There are risks in using eference45;free evaluators based on LLMs to evaluate the quality of dialogue responses.
