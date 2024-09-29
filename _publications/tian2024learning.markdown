---
layout: publication
title: Tinyllm: Learning A Small Student From Multiple Large Language Models
authors: Tian Yijun, Han Yikun, Chen Xiusi, Wang Wei, Chawla Nitesh V.
conference: "Arxiv"
year: 2024
bibkey: tian2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04616"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG']
---
Transferring the reasoning capability from stronger large language models (LLMs) to smaller ones has been quite appealing as smaller LLMs are more flexible to deploy with less expense. Among the existing solutions knowledge distillation stands out due to its outstanding efficiency and generalization. However existing methods suffer from several drawbacks including limited knowledge diversity and the lack of rich contextual information. To solve the problems and facilitate the learning of compact language models we propose TinyLLM a new knowledge distillation paradigm to learn a small student LLM from multiple large teacher LLMs. In particular we encourage the student LLM to not only generate the correct answers but also understand the rationales behind these answers. Given that different LLMs possess diverse reasoning skills we guide the student model to assimilate knowledge from various teacher LLMs. We further introduce an in-context example generator and a teacher-forcing Chain-of-Thought strategy to ensure that the rationales are accurate and grounded in contextually appropriate scenarios. Extensive experiments on six datasets across two reasoning tasks demonstrate the superiority of our method. Results show that TinyLLM can outperform large teacher LLMs significantly despite a considerably smaller model size.
