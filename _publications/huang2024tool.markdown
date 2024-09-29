---
layout: publication
title: Tool Calling Enhancing Medication Consultation Via Retrieval45;augmented Large Language Models
authors: Huang Zhongzhen, Xue Kui, Fan Yongqi, Mu Linjie, Liu Ruoyu, Ruan Tong, Zhang Shaoting, Zhang Xiaofan
conference: "Arxiv"
year: 2024
bibkey: huang2024tool
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17897"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large45;scale language models (LLMs) have achieved remarkable success across various language tasks but suffer from hallucinations and temporal misalignment. To mitigate these shortcomings Retrieval45;augmented generation (RAG) has been utilized to provide external knowledge to facilitate the answer generation. However applying such models to the medical domain faces several challenges due to the lack of domain45;specific knowledge and the intricacy of real45;world scenarios. In this study we explore LLMs with RAG framework for knowledge45;intensive tasks in the medical field. To evaluate the capabilities of LLMs we introduce MedicineQA a multi45;round dialogue benchmark that simulates the real45;world medication consultation scenario and requires LLMs to answer with retrieved evidence from the medicine database. MedicineQA contains 300 multi45;round question45;answering pairs each embedded within a detailed dialogue history highlighting the challenge posed by this knowledge45;intensive task to current LLMs. We further propose a new textit123;Distill45;Retrieve45;Read125; framework instead of the previous textit123;Retrieve45;then45;Read125;. Specifically the distillation and retrieval process utilizes a tool calling mechanism to formulate search queries that emulate the keyword45;based inquiries used by search engines. With experimental results we show that our framework brings notable performance improvements and surpasses the previous counterparts in the evidence retrieval process in terms of evidence retrieval accuracy. This advancement sheds light on applying RAG to the medical domain.
