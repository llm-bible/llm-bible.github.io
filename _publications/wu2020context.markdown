---
layout: publication
title: Context45;guided BERT For Targeted Aspect45;based Sentiment Analysis
authors: Wu Zhengxuan, Ong Desmond C.
conference: "AAAI"
year: 2020
bibkey: wu2020context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.07523"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Transformer']
---
Aspect45;based sentiment analysis (ABSA) and Targeted ASBA (TABSA) allow finer45;grained inferences about sentiment to be drawn from the same text depending on context. For example a given text can have different targets (e.g. neighborhoods) and different aspects (e.g. price or safety) with different sentiment associated with each target45;aspect pair. In this paper we investigate whether adding context to self45;attention models improves performance on (T)ABSA. We propose two variants of Context45;Guided BERT (CG45;BERT) that learn to distribute attention under different contexts. We first adapt a context45;aware Transformer to produce a CG45;BERT that uses context45;guided softmax45;attention. Next we propose an improved Quasi45;Attention CG45;BERT model that learns a compositional attention that supports subtractive attention. We train both models with pretrained BERT on two (T)ABSA datasets SentiHood and SemEval45;2014 (Task 4). Both models achieve new state45;of45;the45;art results with our QACG45;BERT model having the best performance. Furthermore we provide analyses of the impact of context in the our proposed models. Our work provides more evidence for the utility of adding context45;dependencies to pretrained self45;attention45;based language models for context45;based natural language tasks.
