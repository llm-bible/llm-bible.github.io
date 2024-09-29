---
layout: publication
title: M2Lingual Enhancing Multilingual Multi-Turn Instruction Alignment in Large Language Models
authors: Maheshwary Rishabh, Yadav Vikas, Nguyen Hoang, Mahajan Khyati, Madhusudhan Sathwik Tejaswi
conference: "Arxiv"
year: 2024
bibkey: maheshwary2024m2lingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16783"}
  - {name: "Code", url: "https://github.com/ServiceNow/M2Lingual,"}
  - {name: "Code", url: "https://huggingface.co/datasets/ServiceNow-AI/"}
tags: ['Has Code', 'Pretraining Methods', 'Training Techniques']
---
Instruction finetuning (IFT) is critical for aligning Large Language Models (LLMs) to follow instructions. While many effective IFT datasets have been introduced recently they predominantly focus on high-resource languages like English. To better align LLMs across a broad spectrum of languages and tasks we propose a fully synthetic novel taxonomy (Evol) guided Multilingual Multi-turn instruction finetuning dataset called M2Lingual. It is constructed by first selecting a diverse set of seed examples and then utilizing the proposed Evol taxonomy to convert these seeds into complex and challenging multi-turn instructions. We demonstrate the effectiveness of M2Lingual by training LLMs of varying sizes and showcasing the enhanced performance across a diverse set of languages. We contribute the 2 step Evol taxonomy with the guided generation code https://github.com/ServiceNow/M2Lingual, as well as the first fully synthetic general and task-oriented multi-turn multilingual dataset built with Evol - M2Lingual https://huggingface.co/datasets/ServiceNow-AI/ M2Lingual - containing 182K total IFT pairs covering 70 languages and 17+ NLP tasks.
