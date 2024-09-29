---
layout: publication
title: Generative Question Refinement With Deep Reinforcement Learning In Retrieval45;based QA System
authors: Liu Ye, Zhang Chenwei, Yan Xiaohui, Chang Yi, Yu Philip S.
conference: "Arxiv"
year: 2019
bibkey: liu2019generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.05604"}
tags: ['Agentic', 'BERT', 'Model Architecture', 'Reinforcement Learning']
---
In real45;world question45;answering (QA) systems ill45;formed questions such as wrong words ill word order and noisy expressions are common and may prevent the QA systems from understanding and answering them accurately. In order to eliminate the effect of ill45;formed questions we approach the question refinement task and propose a unified model QREFINE to refine the ill45;formed questions to well45;formed question. The basic idea is to learn a Seq2Seq model to generate a new question from the original one. To improve the quality and retrieval performance of the generated questions we make two major improvements 1) To better encode the semantics of ill45;formed questions we enrich the representation of questions with character embedding and the recent proposed contextual word embedding such as BERT besides the traditional context45;free word embeddings; 2) To make it capable to generate desired questions we train the model with deep reinforcement learning techniques that considers an appropriate wording of the generation as an immediate reward and the correlation between generated question and answer as time45;delayed long45;term rewards. Experimental results on real45;world datasets show that the proposed QREFINE method can generate refined questions with more readability but fewer mistakes than the original questions provided by users. Moreover the refined questions also significantly improve the accuracy of answer retrieval.
