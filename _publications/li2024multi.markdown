---
layout: publication
title: 'MIDAS: Multi-level Intent, Domain, And Slot Knowledge Distillation For Multi-turn NLU'
authors: Yan Li, So-eon Kim, Seong-bae Park, Soyeon Caren Han
conference: "Arxiv"
year: 2024
bibkey: li2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.08144'}
  - {name: "Code", url: 'https://github.com/adlnlp/Midas'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Applications']
---
Although Large Language Models (LLMs) can generate coherent text, they often struggle to recognise user intent behind queries. In contrast, Natural Language Understanding (NLU) models interpret the purpose and key information of user input for responsive interactions. Existing NLU models typically map utterances to a dual-level semantic frame, involving sentence-level intent (SI) and word-level slot (WS) labels. However, real-life conversations primarily consist of multi-turn dialogues, requiring the interpretation of complex and extended exchanges. Researchers encounter challenges in addressing all facets of multi-turn dialogue using a unified NLU model. This paper introduces MIDAS, a novel approach leveraging multi-level intent, domain, and slot knowledge distillation for multi-turn NLU. We construct distinct teachers for SI detection, WS filling, and conversation-level domain (CD) classification, each fine-tuned for specific knowledge. A multi-teacher loss is proposed to facilitate the integration of these teachers, guiding a student model in multi-turn dialogue tasks. Results demonstrate the efficacy of our model in improving multi-turn conversation understanding, showcasing the potential for advancements in NLU through multi-level dialogue knowledge distillation. Our implementation is open-sourced on https://github.com/adlnlp/Midas.
