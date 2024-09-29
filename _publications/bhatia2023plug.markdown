---
layout: publication
title: TART A Plug45;and45;play Transformer Module For Task45;agnostic Reasoning
authors: Bhatia Kush, Narayan Avanika, De Sa Christopher, Ré Christopher
conference: "Arxiv"
year: 2023
bibkey: bhatia2023plug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.07536"}
  - {name: "Code", url: "https://github.com/HazyResearch/TART"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) exhibit in45;context learning abilities which enable the same model to perform several tasks without any task45;specific training. In contrast traditional adaptation approaches such as fine45;tuning modify the underlying models for each specific task. In45;context learning however consistently underperforms task45;specific tuning approaches even when presented with the same examples. While most existing approaches (e.g. prompt engineering) focus on the LLMs learned representations to patch this performance gap our analysis actually reveal that LLM representations contain sufficient information to make good predictions. As such we focus on the LLMs reasoning abilities and demonstrate that this performance gap exists due to their inability to perform simple probabilistic reasoning tasks. This raises an intriguing question Are LLMs actually capable of learning how to reason in a task45;agnostic manner We answer this in the affirmative and propose TART which generically improves an LLMs reasoning abilities using a synthetically trained Transformer45;based reasoning module. TART trains this reasoning module in a task45;agnostic manner using only synthetic logistic regression tasks and composes it with an arbitrary real45;world pre45;trained model without any additional training. With a single inference module TART improves performance across different model families (GPT45;Neo Pythia BLOOM) model sizes (100M 45; 6B) tasks (14 NLP binary classification tasks) and even across different modalities (audio and vision). Additionally on the RAFT Benchmark TART improves GPT45;Neo (125M)s performance such that it outperforms BLOOM (176B) and is within 437; of GPT45;3 (175B). Our code and models are available at https://github.com/HazyResearch/TART .
