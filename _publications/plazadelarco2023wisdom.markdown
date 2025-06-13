---
layout: publication
title: 'Wisdom Of Instruction-tuned Language Model Crowds. Exploring Model Label Variation'
authors: Flor Miriam Plaza-del-arco, Debora Nozza, Dirk Hovy
conference: "Arxiv"
year: 2023
bibkey: plazadelarco2023wisdom
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.12973'}
tags: ['Few-Shot']
---
Large Language Models (LLMs) exhibit remarkable text classification
capabilities, excelling in zero- and few-shot learning (ZSL and FSL) scenarios.
However, since they are trained on different datasets, performance varies
widely across tasks between those models. Recent studies emphasize the
importance of considering human label variation in data annotation. However,
how this human label variation also applies to LLMs remains unexplored. Given
this likely model specialization, we ask: Do aggregate LLM labels improve over
individual models (as for human annotators)? We evaluate four recent
instruction-tuned LLMs as annotators on five subjective tasks across four
languages. We use ZSL and FSL setups and label aggregation from human
annotation. Aggregations are indeed substantially better than any individual
model, benefiting from specialization in diverse tasks or languages.
Surprisingly, FSL does not surpass ZSL, as it depends on the quality of the
selected examples. However, there seems to be no good information-theoretical
strategy to select those. We find that no LLM method rivals even simple
supervised models. We also discuss the tradeoffs in accuracy, cost, and
moral/ethical considerations between LLM and human annotation.
