---
layout: publication
title: Can LLM Be A Good Path Planner Based On Prompt Engineering Mitigating The Hallucination For Path Planning
authors: Deng Hourui, Zhang Hongjie, Ou Jie, Feng Chaosheng
conference: "Arxiv"
year: 2024
bibkey: deng2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13184"}
tags: ['Prompting', 'RAG', 'Tools']
---
Spatial reasoning in Large Language Models (LLMs) is the foundation for embodied intelligence. However even in simple maze environments LLMs still encounter challenges in long45;term path45;planning primarily influenced by their spatial hallucination and context inconsistency hallucination by long45;term reasoning. To address this challenge this study proposes an innovative model Spatial45;to45;Relational Transformation and Curriculum Q45;Learning (S2RCQL). To address the spatial hallucination of LLMs we propose the Spatial45;to45;Relational approach which transforms spatial prompts into entity relations and paths representing entity relation chains. This approach fully taps the potential of LLMs in terms of sequential thinking. As a result we design a path45;planning algorithm based on Q45;learning to mitigate the context inconsistency hallucination which enhances the reasoning ability of LLMs. Using the Q45;value of state45;action as auxiliary information for prompts we correct the hallucinations of LLMs thereby guiding LLMs to learn the optimal path. Finally we propose a reverse curriculum learning technique based on LLMs to further mitigate the context inconsistency hallucination. LLMs can rapidly accumulate successful experiences by reducing task difficulty and leveraging them to tackle more complex tasks. We performed comprehensive experiments based on Baidus self45;developed LLM ERNIE45;Bot 4.0. The results showed that our S2RCQL achieved a 2337;45;45;4037; improvement in both success and optimality rates compared with advanced prompt engineering.
