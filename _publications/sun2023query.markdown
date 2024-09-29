---
layout: publication
title: Query45;dependent Prompt Evaluation And Optimization With Offline Inverse RL
authors: Sun Hao, Hüyük Alihan, Van Der Schaar Mihaela
conference: "Arxiv"
year: 2023
bibkey: sun2023query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06553"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning']
---
In this study we aim to enhance the arithmetic reasoning ability of Large Language Models (LLMs) through zero45;shot prompt optimization. We identify a previously overlooked objective of query dependency in such optimization and elucidate two ensuing challenges that impede the successful and economical design of prompt optimization techniques. One primary issue is the absence of an effective method to evaluate prompts during inference when the golden answer is unavailable. Concurrently learning via interactions with the LLMs to navigate the expansive natural language prompting space proves to be resource45;intensive. To address this we introduce Prompt45;OIRL which harnesses offline inverse reinforcement learning to draw insights from offline prompting demonstration data. Such data exists as by45;products when diverse prompts are benchmarked on open45;accessible datasets. With Prompt45;OIRL the query45;dependent prompt optimization objective is achieved by first learning an offline reward model. This model can evaluate any query45;prompt pairs without accessing LLMs. Subsequently a best45;of45;N strategy is deployed to recommend the optimal prompt. Our experimental evaluations across various LLM scales and arithmetic reasoning datasets underscore both the efficacy and economic viability of the proposed approach.
