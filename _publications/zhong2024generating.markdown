---
layout: publication
title: 'Synthet2c: Generating Synthetic Data For Fine-tuning Large Language Models On The Text2cypher Task'
authors: Ziije Zhong, Linqing Zhong, Zhaoze Sun, Qingyun Jin, Zengchang Qin, Xiaofan Zhang
conference: "Arxiv"
year: 2024
bibkey: zhong2024generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.10710'}
  - {name: "Code", url: 'https://github.com/ZGChung/SyntheT2C'}
tags: ['Has Code', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Integrating Large Language Models (LLMs) with existing Knowledge Graph (KG)
databases presents a promising avenue for enhancing LLMs' efficacy and
mitigating their "hallucinations". Given that most KGs reside in graph
databases accessible solely through specialized query languages (e.g., Cypher),
it is critical to connect LLMs with KG databases by automating the translation
of natural language into Cypher queries (termed as "Text2Cypher" task). Prior
efforts tried to bolster LLMs' proficiency in Cypher generation through
Supervised Fine-Tuning (SFT). However, these explorations are hindered by the
lack of annotated datasets of Query-Cypher pairs, resulting from the
labor-intensive and domain-specific nature of such annotation. In this study,
we propose SyntheT2C, a methodology for constructing a synthetic Query-Cypher
pair dataset, comprising two distinct pipelines: (1) LLM-based prompting and
(2) template-filling. SyntheT2C is applied to two medical KG databases,
culminating in the creation of a synthetic dataset, MedT2C. Comprehensive
experiments demonstrate that the MedT2C dataset effectively enhances the
performance of backbone LLMs on Text2Cypher task via SFT. Both the SyntheT2C
codebase and the MedT2C dataset are released in
https://github.com/ZGChung/SyntheT2C.
