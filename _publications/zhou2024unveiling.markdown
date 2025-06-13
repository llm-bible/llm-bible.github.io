---
layout: publication
title: 'Unveiling And Consulting Core Experts In Retrieval-augmented Moe-based Llms'
authors: Xin Zhou, Ping Nie, Yiwen Guo, Haojie Wei, Zhanqiu Zhang, Pasquale Minervini, Ruotian Ma, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2024
bibkey: zhou2024unveiling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15438'}
tags: ['RAG', 'Efficiency and Optimization']
---
Retrieval-Augmented Generation (RAG) significantly improved the ability of
Large Language Models (LLMs) to solve knowledge-intensive tasks. While existing
research seeks to enhance RAG performance by retrieving higher-quality
documents or designing RAG-specific LLMs, the internal mechanisms within LLMs
that contribute to the effectiveness of RAG systems remain underexplored. In
this paper, we aim to investigate these internal mechanisms within the popular
Mixture-of-Expert (MoE)-based LLMs and demonstrate how to improve RAG by
examining expert activations in these LLMs. Our controlled experiments reveal
that several core groups of experts are primarily responsible for RAG-related
behaviors. The activation of these core experts can signify the model's
inclination towards external/internal knowledge and adjust its behavior. For
instance, we identify core experts that can (1) indicate the sufficiency of the
model's internal knowledge, (2) assess the quality of retrieved documents, and
(3) enhance the model's ability to utilize context. Based on these findings, we
propose several strategies to enhance RAG's efficiency and effectiveness
through expert activation. Experimental results across various datasets and
MoE-based LLMs show the effectiveness of our method.
