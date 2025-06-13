---
layout: publication
title: 'Proggen: Generating Named Entity Recognition Datasets Step-by-step With Self-reflexive Large Language Models'
authors: Yuzhao Heng, Chunyuan Deng, Yitong Li, Yue Yu, Yinghao Li, Rongzhi Zhang, Chao Zhang
conference: "Arxiv"
year: 2024
bibkey: heng2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11103"}
tags: ['Training Techniques', 'Prompting']
---
Although Large Language Models (LLMs) exhibit remarkable adaptability across
domains, these models often fall short in structured knowledge extraction tasks
such as named entity recognition (NER). This paper explores an innovative,
cost-efficient strategy to harness LLMs with modest NER capabilities for
producing superior NER datasets. Our approach diverges from the basic
class-conditional prompts by instructing LLMs to self-reflect on the specific
domain, thereby generating domain-relevant attributes (such as category and
emotions for movie reviews), which are utilized for creating attribute-rich
training data. Furthermore, we preemptively generate entity terms and then
develop NER context data around these entities, effectively bypassing the LLMs'
challenges with complex structures. Our experiments across both general and
niche domains reveal significant performance enhancements over conventional
data generation methods while being more cost-effective than existing
alternatives.
