---
layout: publication
title: 'Adapt And Decompose: Efficient Generalization Of Text-to-sql Via Domain Adapted Least-to-most Prompting'
authors: Aseem Arora, Shabbirhussain Bhaisaheb, Harshit Nigam, Manasi Patwardhan, Lovekesh Vig, Gautam Shroff
conference: "Arxiv"
year: 2023
bibkey: arora2023adapt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.02582'}
tags: ['Few-Shot', 'RAG', 'Prompting', 'Training Techniques']
---
Cross-domain and cross-compositional generalization of Text-to-SQL semantic
parsing is a challenging task. Existing Large Language Model (LLM) based
solutions rely on inference-time retrieval of few-shot exemplars from the
training set to synthesize a run-time prompt for each Natural Language (NL)
test query. In contrast, we devise an algorithm which performs offline sampling
of a minimal set-of few-shots from the training data, with complete coverage of
SQL clauses, operators and functions, and maximal domain coverage within the
allowed token length. This allows for synthesis of a fixed Generic Prompt (GP),
with a diverse set-of exemplars common across NL test queries, avoiding
expensive test time exemplar retrieval. We further auto-adapt the GP to the
target database domain (DA-GP), to better handle cross-domain generalization;
followed by a decomposed Least-To-Most-Prompting (LTMP-DA-GP) to handle
cross-compositional generalization. The synthesis of LTMP-DA-GP is an offline
task, to be performed one-time per new database with minimal human
intervention. Our approach demonstrates superior performance on the KaggleDBQA
dataset, designed to evaluate generalizability for the Text-to-SQL task. We
further showcase consistent performance improvement of LTMP-DA-GP over GP,
across LLMs and databases of KaggleDBQA, highlighting the efficacy and model
agnostic benefits of our prompt based adapt and decompose approach.
