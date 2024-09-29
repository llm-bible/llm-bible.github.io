---
layout: publication
title: Large Language Models Can Learn Temporal Reasoning
authors: Xiong Siheng, Payani Ali, Kompella Ramana, Fekri Faramarz
conference: "Arxiv"
year: 2024
bibkey: xiong2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06853"}
tags: ['Distillation', 'Efficiency And Optimization', 'Tools']
---
While large language models (LLMs) have demonstrated remarkable reasoning capabilities they are not without their flaws and inaccuracies. Recent studies have introduced various methods to mitigate these limitations. Temporal reasoning (TR) in particular presents a significant challenge for LLMs due to its reliance on diverse temporal concepts and intricate temporal logic. In this paper we propose TG45;LLM a novel framework towards language45;based TR. Instead of reasoning over the original context we adopt a latent representation temporal graph (TG) that enhances the learning of TR. A synthetic dataset (TGQA) which is fully controllable and requires minimal supervision is constructed for fine45;tuning LLMs on this text45;to45;TG translation task. We confirmed in experiments that the capability of TG translation learned on our dataset can be transferred to other TR tasks and benchmarks. On top of that we teach LLM to perform deliberate reasoning over the TGs via Chain45;of45;Thought (CoT) bootstrapping and graph data augmentation. We observed that those strategies which maintain a balance between usefulness and diversity bring more reliable CoTs and final results than the vanilla CoT distillation.
