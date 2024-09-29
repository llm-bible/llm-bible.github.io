---
layout: publication
title: "PEDAL: Enhancing Greedy Decoding With Large Language Models Using Diverse Exemplars"
authors: Prabhu Sumanth
conference: "Arxiv"
year: 2024
bibkey: prabhu2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08869"}
tags: ['Applications', 'Language Modeling', 'Prompting']
---
Self-ensembling techniques with diverse reasoning paths such as Self-Consistency have demonstrated remarkable performance gains in text generation with Large Language Models (LLMs). However such techniques depend on the availability of an accurate answer extraction process to aggregate across multiple outputs. Moreover they acquire higher inference cost in comparison to Greedy Decoding due to generation of relatively higher number of output tokens. Research has shown that the free form text outputs from Self-Consistency can be aggregated reliably using LLMs to produce the final output. Additionally recent advancements in LLM inference have demonstrated that usage of diverse exemplars in prompts have the ability to induce diversity in the LLM outputs. Such proven techniques can be easily extended to self-ensembling based approaches to achieve enhanced results in text generation. In this paper we introduce PEDAL (Prompts based on Exemplar Diversity Aggregated using LLMs) a hybrid self-ensembling approach that combines the strengths of diverse exemplar based prompts and LLM based aggregation to achieve improvement in overall performance. On the publicly available SVAMP and ARC datasets our experiments reveal that PEDAL can achieve better accuracy than Greedy Decoding based strategies with lower inference cost compared to Self Consistency based approaches.
