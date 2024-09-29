---
layout: publication
title: Can Perplexity Predict Fine45;tuning Performance An Investigation Of Tokenization Effects On Sequential Language Models For Nepali
authors: Luitel Nishant, Bekoju Nirajan, Sah Anand Kumar, Shakya Subarna
conference: "Arxiv"
year: 2024
bibkey: luitel2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18071"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tokenization', 'Transformer']
---
Recent language models use subwording mechanisms to handle Out45;of45;Vocabulary(OOV) words seen during test time and their generation capacity is generally measured using perplexity an intrinsic metric. It is known that increasing the subword granularity results in a decrease of perplexity value. However the study of how subwording affects the understanding capacity of language models has been very few and only limited to a handful of languages. To reduce this gap we used 6 different tokenization schemes to pretrain relatively small language models in Nepali and used the representations learned to finetune on several downstream tasks. Although byte45;level BPE algorithm has been used in recent models like GPT RoBERTa we show that on average they are sub45;optimal in comparison to algorithms such as SentencePiece in finetuning performances for Nepali. Additionally similar recent studies have focused on the Bert45;based language model. We however pretrain and finetune sequential transformer45;based language models.
