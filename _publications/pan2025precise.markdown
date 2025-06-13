---
layout: publication
title: 'Precise Localization Of Memories: A Fine-grained Neuron-level Knowledge Editing Technique For Llms'
authors: Haowen Pan, Xiaozhi Wang, Yixin Cao, Zenglin Shi, Xun Yang, Juanzi Li, Meng Wang
conference: "Arxiv"
year: 2025
bibkey: pan2025precise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01090"}
tags: ['Uncategorized']
---
Knowledge editing aims to update outdated information in Large Language
Models (LLMs). A representative line of study is locate-then-edit methods,
which typically employ causal tracing to identify the modules responsible for
recalling factual knowledge about entities. However, we find these methods are
often sensitive only to changes in the subject entity, leaving them less
effective at adapting to changes in relations. This limitation results in poor
editing locality, which can lead to the persistence of irrelevant or inaccurate
facts, ultimately compromising the reliability of LLMs. We believe this issue
arises from the insufficient precision of knowledge localization. To address
this, we propose a Fine-grained Neuron-level Knowledge Editing (FiNE) method
that enhances editing locality without affecting overall success rates. By
precisely identifying and modifying specific neurons within feed-forward
networks, FiNE significantly improves knowledge localization and editing.
Quantitative experiments demonstrate that FiNE efficiently achieves better
overall performance compared to existing techniques, providing new insights
into the localization and modification of knowledge within LLMs.
