---
layout: publication
title: 'IRCAN: Mitigating Knowledge Conflicts In LLM Generation Via Identifying And Reweighting Context-aware Neurons'
authors: Dan Shi, Renren Jin, Tianhao Shen, Weilong Dong, Xinwei Wu, Deyi Xiong
conference: "Arxiv"
year: 2024
bibkey: shi2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18406"}
  - {name: "Code", url: "https://github.com/danshi777/IRCAN"}
tags: ['Has Code', 'Tools']
---
It is widely acknowledged that large language models (LLMs) encode a vast
reservoir of knowledge after being trained on mass data. Recent studies
disclose knowledge conflicts in LLM generation, wherein outdated or incorrect
parametric knowledge (i.e., encoded knowledge) contradicts new knowledge
provided in the context. To mitigate such knowledge conflicts, we propose a
novel framework, IRCAN (Identifying and Reweighting Context-Aware Neurons) to
capitalize on neurons that are crucial in processing contextual cues.
Specifically, IRCAN first identifies neurons that significantly contribute to
context processing, utilizing a context-aware attribution score derived from
integrated gradients. Subsequently, the identified context-aware neurons are
strengthened via reweighting. In doing so, we steer LLMs to generate
context-sensitive outputs with respect to the new knowledge provided in the
context. Extensive experiments conducted across a variety of models and tasks
demonstrate that IRCAN not only achieves remarkable improvements in handling
knowledge conflicts but also offers a scalable, plug-and-play solution that can
be integrated seamlessly with existing models. Our codes are released at
https://github.com/danshi777/IRCAN.
