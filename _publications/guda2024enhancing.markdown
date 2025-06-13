---
layout: publication
title: 'QMOS: Enhancing Llms For Telecommunication With Question Masked Loss And Option Shuffling'
authors: Blessed Guda, Gabrial Zencha Ashungafac, Lawrence Francis, Carlee Joe-wong
conference: "IEEE Globecom Workshop 2024"
year: 2024
bibkey: guda2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14175"}
tags: ['Model Architecture', 'Tools', 'TACL', 'RAG', 'GPT', 'ACL', 'Prompting', 'Applications']
---
Large Language models (LLMs) have brought about substantial advancements in
the field of Question Answering (QA) systems. These models do remarkably well
in addressing intricate inquiries in a variety of disciplines. However, because
of domain-specific vocabulary, complex technological concepts, and the
requirement for exact responses applying LLMs to specialized sectors like
telecommunications presents additional obstacles. GPT-3.5 has been used in
recent work, to obtain noteworthy accuracy for telecom-related questions in a
Retrieval Augmented Generation (RAG) framework. Notwithstanding these
developments, the practical use of models such as GPT-3.5 is restricted by
their proprietary nature and high computing demands. This paper introduces
QMOS, an innovative approach which uses a Question-Masked loss and Option
Shuffling trick to enhance the performance of LLMs in answering Multiple-Choice
Questions in the telecommunications domain. Our focus was on using opensource,
smaller language models (Phi-2 and Falcon-7B) within an enhanced RAG framework.
Our multi-faceted approach involves several enhancements to the whole LLM-RAG
pipeline of finetuning, retrieval, prompt engineering and inference. Our
approaches significantly outperform existing results, achieving accuracy
improvements from baselines of 24.70% to 49.30% with Falcon-7B and from 42.07%
to 84.65% with Phi-2.
