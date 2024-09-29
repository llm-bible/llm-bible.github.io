---
layout: publication
title: Reasoning Over History Context Aware Visual Dialog
authors: Shah Muhammad A., Mehri Shikib, Srinivasan Tejas
conference: "Arxiv"
year: 2020
bibkey: shah2020reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.00669"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning']
---
While neural models have been shown to exhibit strong performance on single45;turn visual question answering (VQA) tasks extending VQA to a multi45;turn conversational setting remains a challenge. One way to address this challenge is to augment existing strong neural VQA models with the mechanisms that allow them to retain information from previous dialog turns. One strong VQA model is the MAC network which decomposes a task into a series of attention45;based reasoning steps. However since the MAC network is designed for single45;turn question answering it is not capable of referring to past dialog turns. More specifically it struggles with tasks that require reasoning over the dialog history particularly coreference resolution. We extend the MAC network architecture with Context45;aware Attention and Memory (CAM) which attends over control states in past dialog turns to determine the necessary reasoning operations for the current question. MAC nets with CAM achieve up to 98.2537; accuracy on the CLEVR45;Dialog dataset beating the existing state45;of45;the45;art by 3037; (absolute). Our error analysis indicates that with CAM the models performance particularly improved on questions that required coreference resolution.
