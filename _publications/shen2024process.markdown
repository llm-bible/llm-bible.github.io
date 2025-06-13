---
layout: publication
title: 'Proctag: Process Tagging For Assessing The Efficacy Of Document Instruction Data'
authors: Yufan Shen, Chuwei Luo, Zhaoqing Zhu, Yang Chen, Qi Zheng, Zhi Yu, Jiajun Bu, Cong Yao
conference: "Arxiv"
year: 2024
bibkey: shen2024process
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12358"}
  - {name: "Code", url: "https://github.com/AlibabaResearch/AdvancedLiterateMachinery/tree/main/DocumentUnderstanding/ProcTag"}
tags: ['Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting']
---
Recently, large language models (LLMs) and multimodal large language models
(MLLMs) have demonstrated promising results on document visual question
answering (VQA) task, particularly after training on document instruction
datasets. An effective evaluation method for document instruction data is
crucial in constructing instruction data with high efficacy, which, in turn,
facilitates the training of LLMs and MLLMs for document VQA. However, most
existing evaluation methods for instruction data are limited to the textual
content of the instructions themselves, thereby hindering the effective
assessment of document instruction datasets and constraining their
construction. In this paper, we propose ProcTag, a data-oriented method that
assesses the efficacy of document instruction data. ProcTag innovatively
performs tagging on the execution process of instructions rather than the
instruction text itself. By leveraging the diversity and complexity of these
tags to assess the efficacy of the given dataset, ProcTag enables selective
sampling or filtering of document instructions. Furthermore, DocLayPrompt, a
novel semi-structured layout-aware document prompting strategy, is proposed for
effectively representing documents. Experiments demonstrate that sampling
existing open-sourced and generated document VQA/instruction datasets with
ProcTag significantly outperforms current methods for evaluating instruction
data. Impressively, with ProcTag-based sampling in the generated document
datasets, only 30.5% of the document instructions are required to achieve
100% efficacy compared to the complete dataset. The code is publicly available
at
https://github.com/AlibabaResearch/AdvancedLiterateMachinery/tree/main/DocumentUnderstanding/ProcTag.
