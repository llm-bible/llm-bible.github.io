---
layout: publication
title: 'Synthet2c: Generating Synthetic Data For Fine-tuning Large Language Models On The Text2cypher Task'
authors: Zhong Ziije, Zhong Linqing, Sun Zhaoze, Jin Qingyun, Qin Zengchang, Zhang Xiaofan
conference: "Arxiv"
year: 2024
bibkey: zhong2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10710"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Integrating Large Language Models (LLMs) with existing Knowledge Graph (KG)
databases presents a promising avenue for enhancing LLMs' efficacy and
mitigating their "hallucinations". Given that most KGs reside in graph
databases accessible solely through specialized query languages (e.g., Cypher),
there exists a critical need to bridge the divide between LLMs and KG databases
by automating the translation of natural language into Cypher queries (commonly
termed the "Text2Cypher" task). Prior efforts tried to bolster LLMs'
proficiency in Cypher generation through Supervised Fine-Tuning. However, these
explorations are hindered by the lack of annotated datasets of Query-Cypher
pairs, resulting from the labor-intensive and domain-specific nature of
annotating such datasets. In this study, we propose SyntheT2C, a methodology
for constructing a synthetic Query-Cypher pair dataset, comprising two distinct
pipelines: (1) LLM-based prompting and (2) template-filling. SyntheT2C
facilitates the generation of extensive Query-Cypher pairs with values sampled
from an underlying Neo4j graph database. Subsequently, SyntheT2C is applied to
two medical databases, culminating in the creation of a synthetic dataset,
MedT2C. Comprehensive experiments demonstrate that the MedT2C dataset
effectively enhances the performance of backbone LLMs on the Text2Cypher task.
Both the SyntheT2C codebase and the MedT2C dataset will be released soon.
