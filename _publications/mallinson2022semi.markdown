---
layout: publication
title: Edit5 Semi45;autoregressive Text45;editing With T5 Warm45;start
authors: Mallinson Jonathan, Adamek Jakub, Malmi Eric, Severyn Aliaksei
conference: "Arxiv"
year: 2022
bibkey: mallinson2022semi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.12209"}
tags: ['GPT', 'Merging', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
We present EdiT5 45; a novel semi45;autoregressive text45;editing model designed to combine the strengths of non45;autoregressive text45;editing and autoregressive decoding. EdiT5 is faster during inference than conventional sequence45;to45;sequence (seq2seq) models while being capable of modelling flexible input45;output transformations. This is achieved by decomposing the generation process into three sub45;tasks (1) tagging to decide on the subset of input tokens to be preserved in the output (2) re45;ordering to define their order in the output text and (3) insertion to infill the missing tokens that are not present in the input. The tagging and re45;ordering steps which are responsible for generating the largest portion of the output are non45;autoregressive while the insertion step uses an autoregressive decoder. Depending on the task EdiT5 on average requires significantly fewer autoregressive steps demonstrating speedups of up to 25x when compared to seq2seq models. Quality45;wise EdiT5 is initialized with a pre45;trained T5 checkpoint yielding comparable performance to T5 in high45;resource settings when evaluated on three NLG tasks Sentence Fusion Grammatical Error Correction and Decontextualization while clearly outperforming T5 in low45;resource settings.
