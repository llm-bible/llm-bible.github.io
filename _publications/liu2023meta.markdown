---
layout: publication
title: "Meta Semantic Template For Evaluation Of Large Language Models"
authors: Liu Yachuan, Chen Liang, Wang Jindong, Mei Qiaozhu, Xie Xing
conference: "Arxiv"
year: 2023
bibkey: liu2023meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01448"}
tags: ['Ethics And Bias', 'RAG', 'Training Techniques']
---
Do large language models (LLMs) genuinely understand the semantics of the language or just memorize the training data The recent concern on potential data contamination of LLMs has raised awareness of the community to conduct research on LLMs evaluation. In this paper we propose MSTemp an approach that creates meta semantic templates to evaluate the semantic understanding ability of LLMs. The core of MSTemp is not to perform evaluation directly on existing benchmark datasets but to generate new out-of-distribution (OOD) evaluation sets using existing datasets as seeds. Specifically for a given sentence MSTemp leverages another language model to generate new samples while preserving its semantics. The new samples are called semantic templates to the original sentence. Then MSTemp generates evaluation samples via sentence parsing and random word replacement on the semantic templates. MSTemp is highly flexible dynamic and cost-effective. Our initial experiments show that MSTemp-generated samples can significantly reduce the performance of LLMs using existing datasets as seeds. We hope this initial work can shed light on future research of LLMs evaluation.
