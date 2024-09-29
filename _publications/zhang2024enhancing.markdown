---
layout: publication
title: Enhancing Multi-hop Reasoning through Knowledge Erasure in Large Language Model Editing
authors: Zhang Mengqi, Fang Bowen, Liu Qiang, Ren Pengjie, Wu Shu, Chen Zhumin, Wang Liang
conference: "Arxiv"
year: 2024
bibkey: zhang2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12456"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Tools']
---
Large language models (LLMs) face challenges with internal knowledge inaccuracies and outdated information. Knowledge editing has emerged as a pivotal approach to mitigate these issues. Although current knowledge editing techniques exhibit promising performance in single-hop reasoning tasks they show limitations when applied to multi-hop reasoning. Drawing on cognitive neuroscience and the operational mechanisms of LLMs we hypothesize that the residual single-hop knowledge after editing causes edited models to revert to their original answers when processing multi-hop questions thereby undermining their performance in multihop reasoning tasks. To validate this hypothesis we conduct a series of experiments that empirically confirm our assumptions. Building on the validated hypothesis we propose a novel knowledge editing method that incorporates a Knowledge Erasure mechanism for Large language model Editing (KELE). Specifically we design an erasure function for residual knowledge and an injection function for new knowledge. Through joint optimization we derive the optimal recall vector which is subsequently utilized within a rank-one editing framework to update the parameters of targeted model layers. Extensive experiments on GPT-J and GPT-2 XL demonstrate that KELE substantially enhances the multi-hop reasoning capability of edited LLMs.
