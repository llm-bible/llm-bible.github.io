---
layout: publication
title: Llama45;reviewer Advancing Code Review Automation With Large Language Models Through Parameter45;efficient Fine45;tuning
authors: Lu Junyi, Yu Lei, Li Xiaojia, Yang Li, Zuo Chun
conference: "Arxiv"
year: 2023
bibkey: lu2023llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11148"}
tags: ['Efficiency And Optimization', 'RAG', 'Survey Paper', 'Tools', 'Training Techniques']
---
The automation of code review activities a long45;standing pursuit in software engineering has been primarily addressed by numerous domain45;specific pre45;trained models. Despite their success these models frequently demand extensive resources for pre45;training from scratch. In contrast Large Language Models (LLMs) provide an intriguing alternative given their remarkable capabilities when supplemented with domain45;specific knowledge. However their potential for automating code review tasks remains largely unexplored. In response to this research gap we present LLaMA45;Reviewer an innovative framework that leverages the capabilities of LLaMA a popular LLM in the realm of code review. Mindful of resource constraints this framework employs parameter45;efficient fine45;tuning (PEFT) methods delivering high performance while using less than 137; of trainable parameters. An extensive evaluation of LLaMA45;Reviewer is conducted on two diverse publicly available datasets. Notably even with the smallest LLaMA base model consisting of 6.7B parameters and a limited number of tuning epochs LLaMA45;Reviewer equals the performance of existing code45;review45;focused models. The ablation experiments provide insights into the influence of various fine45;tuning process components including input representation instruction tuning and different PEFT methods. To foster continuous progress in this field the code and all PEFT45;weight plugins have been made open45;source.
