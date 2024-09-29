---
layout: publication
title: Instructing Large Language Models To Identify And Ignore Irrelevant Conditions
authors: Wu Zhenyu, Shen Chao, Jiang Meng
conference: "Arxiv"
year: 2024
bibkey: wu2024instructing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12744"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Prompting']
---
Math word problem (MWP) solving requires generating a reasoning path based on a given problem description that often contains irrelevant conditions. Existing chain45;of45;thought (CoT) prompting methods elicited multi45;step reasoning abilities of large language models (LLMs) to solve MWPs. However they were seriously confused by the irrelevant conditions resulting in low accuracy. In this paper we propose a novel approach named I^3C that instructs LLMs to identify and ignore irrelevant conditions. It identifies a set of irrelevant condition candidates that have a weak semantic relevance with the question. Then it prompts LLMs to verify the irrelevant conditions. Lastly it instructs the LLMs with the verification on relevant and irrelevant conditions to avoid confusion and improve reasoning paths. Moreover we propose to select (problem reasoning paths) pairs as demonstrations to enhance I^3C with few45;shot reasoning. We develop I^3C45;Select that selects the most confusing problems based on the semantic relevance measurement. We conduct extensive experiments on eight MWP datasets. I^3C can be combined with any CoT prompting methods to improve the performance of solving MWPs. Notably with GPT45;3.545;Turbo and I^3C45;Select we achieve an accuracy of 96.0 and 94.1 on GSM45;IC245;1K and GSM45;ICM45;1K respectively significantly outperforming the state45;of45;the45;art few45;shot prompting method Complex45;CoT by +11.7 and +11.1. Our implementation is made publicly available at https://wzy6642.github.io/I3C.github.io/.
