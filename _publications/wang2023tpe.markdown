---
layout: publication
title: TPE Towards Better Compositional Reasoning Over Conceptual Tools With Multi-persona Collaboration
authors: Wang Hongru, Wang Huimin, Wang Lingzhi, Hu Minda, Wang Rui, Xue Boyang, Lu Hongyuan, Mi Fei, Wong Kam-fai
conference: "Arxiv"
year: 2023
bibkey: wang2023tpe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16090"}
tags: ['Applications', 'Interpretability And Explainability', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have demonstrated exceptional performance in planning the use of various functional tools such as calculators and retrievers particularly in question-answering tasks. In this paper we expand the definition of these tools centering on conceptual tools within the context of dialogue systems. A conceptual tool specifies a cognitive concept that aids systematic or investigative thought. These conceptual tools play important roles in practice such as multiple psychological or tutoring strategies being dynamically applied in a single turn to compose helpful responses. To further enhance the reasoning and planning capability of LLMs with these conceptual tools we introduce a multi-persona collaboration framework Think-Plan-Execute (TPE). This framework decouples the response generation process into three distinct roles Thinker Planner and Executor. Specifically the Thinker analyzes the internal status exhibited in the dialogue context such as user emotions and preferences to formulate a global guideline. The Planner then generates executable plans to call different conceptual tools (e.g. sources or strategies) while the Executor compiles all intermediate results into a coherent response. This structured approach not only enhances the explainability and controllability of responses but also reduces token redundancy. We demonstrate the effectiveness of TPE across various dialogue response generation tasks including multi-source (FoCus) and multi-strategy interactions (CIMA and PsyQA). This reveals its potential to handle real-world dialogue interactions that require more complicated tool learning beyond just functional tools. The full code and data will be released for reproduction.
