---
layout: publication
title: Instruction-tuning Aligns Llms To The Human Brain
authors: Aw Khai Loong, Montariol Syrielle, Alkhamissi Badr, Schrimpf Martin, Bosselut Antoine
conference: "Arxiv"
year: 2023
bibkey: aw2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.00575"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning']
---
Instruction-tuning is a widely adopted finetuning method that enables large language models (LLMs) to generate output that more closely resembles human responses. However no studies have shown that instruction-tuning actually teaches LLMs to process language in a similar manner as humans. We investigate the effect of instruction-tuning on aligning LLM and human language processing mechanisms in two ways (1) brain alignment the similarity of LLM internal representations to neural activity in the human language system and (2) behavioral alignment the similarity of LLM and human behavior on a reading task. We assess 25 vanilla and instruction-tuned LLMs on three datasets involving humans reading naturalistic stories and sentences and find that instruction-tuning generally enhances brain alignment (~637;) but has no similar effect on behavioral alignment. To identify factors underlying this improvement in brain alignment we compute correlations between brain alignment and various LLM properties such as model size problem-solving and world knowledge understanding. Notably we find a strong positive correlation between brain alignment and model size (r = 0.95) as well as performance on tasks requiring world knowledge (r = 0.81). Our results demonstrate that instruction-tuning LLMs improves both world knowledge representations and brain alignment suggesting that the mechanisms that encode world knowledge in LLMs also improve representational alignment to the human brain.
