---
layout: publication
title: Doremi Grounding Language Model By Detecting And Recovering From Plan-execution Misalignment
authors: Guo Yanjiang, Wang Yen-jen, Zha Lihan, Jiang Zheyuan, Chen Jianyu
conference: "Arxiv"
year: 2023
bibkey: guo2023doremi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.00329"}
  - {name: "Code", url: "https://sites.google.com/view/doremi-paper"}
tags: ['Has Code', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) encode a vast amount of semantic knowledge and possess remarkable understanding and reasoning capabilities. Previous work has explored how to ground LLMs in robotic tasks to generate feasible and executable textual plans. However low-level execution in the physical world may deviate from the high-level textual plan due to environmental perturbations or imperfect controller design. In this paper we propose a novel language model grounding framework that enables immediate Detection and Recovery from Misalignments between plan and execution. Specifically we leverage LLMs to play a dual role aiding not only in high-level planning but also generating constraints that can indicate misalignment during execution. Then vision language models (VLMs) are utilized to detect constraint violations continuously. Our pipeline can monitor the low-level execution and enable timely recovery if certain plan-execution misalignment occurs. Experiments on various complex tasks including robot arms and humanoid robots demonstrate that our method can lead to higher task success rates and shorter task completion times. Videos of DoReMi are available at urlhttps://sites.google.com/view/doremi-paper}.
