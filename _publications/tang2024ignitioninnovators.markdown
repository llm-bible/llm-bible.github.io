---
layout: publication
title: 'Ignitioninnovators At "discharge Me!": Chain-of-thought Instruction Finetuning Large Language Models For Discharge Summaries'
authors: An Quang Tang, Xiuzhen Zhang, Minh Ngoc Dinh
conference: "Arxiv"
year: 2024
bibkey: tang2024ignitioninnovators
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17636"}
  - {name: "Code", url: "https://github.com/antangrocket1312/Discharge_LLM"}
tags: ['Tools', 'Has Code', 'Prompting']
---
This paper presents our proposed approach to the Discharge Me! shared task,
collocated with the 23th Workshop on Biomedical Natural Language Processing
(BioNLP). In this work, we develop an LLM-based framework for solving the
Discharge Summary Documentation (DSD) task, i.e., generating the two critical
target sections `Brief Hospital Course' and `Discharge Instructions' in the
discharge summary. By streamlining the recent instruction-finetuning process on
LLMs, we explore several prompting strategies for optimally adapting LLMs to
specific generation task of DSD. Experimental results show that providing a
clear output structure, complimented by a set of comprehensive
Chain-of-Thoughts (CoT) questions, effectively improves the model's reasoning
capability, and thereby, enhancing the structural correctness and faithfulness
of clinical information in the generated text. Source code is available at:
https://github.com/antangrocket1312/Discharge_LLM
