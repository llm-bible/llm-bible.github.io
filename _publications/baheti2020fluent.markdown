---
layout: publication
title: 'Fluent Response Generation For Conversational Question Answering'
authors: Ashutosh Baheti, Alan Ritter, Kevin Small
conference: "Arxiv"
year: 2020
bibkey: baheti2020fluent
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2005.10464'}
  - {name: "Code", url: 'https://github.com/abaheti95/QADialogSystem'}
tags: ['Agentic', 'Has Code', 'Training Techniques', 'BERT', 'Applications', 'Model Architecture']
---
Question answering (QA) is an important aspect of open-domain conversational
agents, garnering specific research focus in the conversational QA (ConvQA)
subtask. One notable limitation of recent ConvQA efforts is the response being
answer span extraction from the target corpus, thus ignoring the natural
language generation (NLG) aspect of high-quality conversational agents. In this
work, we propose a method for situating QA responses within a SEQ2SEQ NLG
approach to generate fluent grammatical answer responses while maintaining
correctness. From a technical perspective, we use data augmentation to generate
training data for an end-to-end system. Specifically, we develop Syntactic
Transformations (STs) to produce question-specific candidate answer responses
and rank them using a BERT-based classifier (Devlin et al., 2019). Human
evaluation on SQuAD 2.0 data (Rajpurkar et al., 2018) demonstrate that the
proposed model outperforms baseline CoQA and QuAC models in generating
conversational responses. We further show our model's scalability by conducting
tests on the CoQA dataset. The code and data are available at
https://github.com/abaheti95/QADialogSystem.
