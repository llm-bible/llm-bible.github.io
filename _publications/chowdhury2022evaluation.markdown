---
layout: publication
title: "On The Evaluation Of Answer-agnostic Paragraph-level Multi-question Generation"
authors: Chowdhury Jishnu Ray, Mahata Debanjan, Caragea Cornelia
conference: "Arxiv"
year: 2022
bibkey: chowdhury2022evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.04464"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
We study the task of predicting a set of salient questions from a given paragraph without any prior knowledge of the precise answer. We make two main contributions. First we propose a new method to evaluate a set of predicted questions against the set of references by using the Hungarian algorithm to assign predicted questions to references before scoring the assigned pairs. We show that our proposed evaluation strategy has better theoretical and practical properties compared to prior methods because it can properly account for the coverage of references. Second we compare different strategies to utilize a pre-trained seq2seq model to generate and select a set of questions related to a given paragraph. The code is available.
