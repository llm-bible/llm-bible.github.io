---
layout: publication
title: ERNIE45;GEN An Enhanced Multi45;flow Pre45;training And Fine45;tuning Framework For Natural Language Generation
authors: Xiao Dongling, Zhang Han, Li Yukun, Sun Yu, Tian Hao, Wu Hua, Wang Haifeng
conference: "Arxiv"
year: 2020
bibkey: xiao2020ernie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.11314"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Tools', 'Training Techniques']
---
Current pre45;training works in natural language generation pay little attention to the problem of exposure bias on downstream tasks. To address this issue we propose an enhanced multi45;flow sequence to sequence pre45;training and fine45;tuning framework named ERNIE45;GEN which bridges the discrepancy between training and inference with an infilling generation mechanism and a noise45;aware generation method. To make generation closer to human writing patterns this framework introduces a span45;by45;span generation flow that trains the model to predict semantically45;complete spans consecutively rather than predicting word by word. Unlike existing pre45;training methods ERNIE45;GEN incorporates multi45;granularity target sampling to construct pre45;training data which enhances the correlation between encoder and decoder. Experimental results demonstrate that ERNIE45;GEN achieves state45;of45;the45;art results with a much smaller amount of pre45;training data and parameters on a range of language generation tasks including abstractive summarization (Gigaword and CNN/DailyMail) question generation (SQuAD) dialogue generation (Persona45;Chat) and generative question answering (CoQA).
