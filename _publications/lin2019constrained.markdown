---
layout: publication
title: Commongen A Constrained Text Generation Challenge For Generative Commonsense Reasoning
authors: Lin Bill Yuchen, Zhou Wangchunshu, Shen Ming, Zhou Pei, Bhagavatula Chandra, Choi Yejin, Ren Xiang
conference: "Arxiv"
year: 2019
bibkey: lin2019constrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.03705"}
tags: ['Applications', 'Language Modeling']
---
Recently large45;scale pre45;trained language models have demonstrated impressive performance on several commonsense45;reasoning benchmark datasets. However building machines with commonsense to compose realistically plausible sentences remains challenging. In this paper we present a constrained text generation task CommonGen associated with a benchmark dataset to explicitly test machines for the ability of generative commonsense reasoning. Given a set of common concepts (e.g. 123;dog frisbee catch throw125;); the task is to generate a coherent sentence describing an everyday scenario using these concepts (e.g. a man throws a frisbee and his dog catches it). The CommonGen task is challenging because it inherently requires 1) relational reasoning with background commonsense knowledge and 2) compositional generalization ability to work on unseen concept combinations. Our dataset constructed through a combination of crowdsourced and existing caption corpora consists of 79k commonsense descriptions over 35k unique concept45;sets. Experiments show that there is a large gap between state45;of45;the45;art text generation models (e.g. T5) and human performance. Furthermore we demonstrate that the learned generative commonsense reasoning capability can be transferred to improve downstream tasks such as CommonsenseQA by generating additional context.
