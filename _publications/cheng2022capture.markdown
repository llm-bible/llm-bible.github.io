---
layout: publication
title: Capture Salient Historical Information A Fast And Accurate Non45;autoregressive Model For Multi45;turn Spoken Language Understanding
authors: Cheng Lizhi, Jia Weijia, Yang Wenmian
conference: "Arxiv"
year: 2022
bibkey: cheng2022capture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.12209"}
tags: ['Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Spoken Language Understanding (SLU) a core component of the task45;oriented dialogue system expects a shorter inference facing the impatience of human users. Existing work increases inference speed by designing non45;autoregressive models for single45;turn SLU tasks but fails to apply to multi45;turn SLU in confronting the dialogue history. The intuitive idea is to concatenate all historical utterances and utilize the non45;autoregressive models directly. However this approach seriously misses the salient historical information and suffers from the uncoordinated45;slot problems. To overcome those shortcomings we propose a novel model for multi45;turn SLU named Salient History Attention with Layer45;Refined Transformer (SHA45;LRT) which composes of an SHA module a Layer45;Refined Mechanism (LRM) and a Slot Label Generation (SLG) task. SHA captures salient historical information for the current dialogue from both historical utterances and results via a well45;designed history45;attention mechanism. LRM predicts preliminary SLU results from Transformers middle states and utilizes them to guide the final prediction and SLG obtains the sequential dependency information for the non45;autoregressive encoder. Experiments on public datasets indicate that our model significantly improves multi45;turn SLU performance (17.537; on Overall) with accelerating (nearly 15 times) the inference process over the state45;of45;the45;art baseline as well as effective on the single45;turn SLU tasks.
