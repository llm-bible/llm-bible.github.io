---
layout: publication
title: Option Comparison Network For Multiple45;choice Reading Comprehension
authors: Ran Qiu, Li Peng, Hu Weiwei, Zhou Jie
conference: "Arxiv"
year: 2019
bibkey: ran2019option
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1903.03033"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Transformer']
---
Multiple45;choice reading comprehension (MCRC) is the task of selecting the correct answer from multiple options given a question and an article. Existing MCRC models typically either read each option independently or compute a fixed45;length representation for each option before comparing them. However humans typically compare the options at multiple45;granularity level before reading the article in detail to make reasoning more efficient. Mimicking humans we propose an option comparison network (OCN) for MCRC which compares options at word45;level to better identify their correlations to help reasoning. Specially each option is encoded into a vector sequence using a skimmer to retain fine45;grained information as much as possible. An attention mechanism is leveraged to compare these sequences vector45;by45;vector to identify more subtle correlations between options which is potentially valuable for reasoning. Experimental results on the human English exam MCRC dataset RACE show that our model outperforms existing methods significantly. Moreover it is also the first model that surpasses Amazon Mechanical Turker performance on the whole dataset.
