---
layout: publication
title: Stepwise Extractive Summarization and Planning with Structured Transformers
authors: Narayan Shashi, Maynez Joshua, Adamek Jakub, Pighin Daniele, Bratanič Blaž, Mcdonald Ryan
conference: "Arxiv"
year: 2020
bibkey: narayan2020stepwise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.02744"}
tags: ['ARXIV', 'Applications', 'BERT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
We propose encoder-centric stepwise models for extractive summarization using structured transformers -- HiBERT and Extended Transformers. We enable stepwise summarization by injecting the previously generated summary into the structured transformer as an auxiliary sub-structure. Our models are not only efficient in modeling the structure of long inputs but they also do not rely on task-specific redundancy-aware modeling making them a general purpose extractive content planner for different tasks. When evaluated on CNN/DailyMail extractive summarization stepwise models achieve state-of-the-art performance in terms of Rouge without any redundancy aware modeling or sentence filtering. This also holds true for Rotowire table-to-text generation where our models surpass previously reported metrics for content selection planning and ordering highlighting the strength of stepwise modeling. Amongst the two structured transformers we test stepwise Extended Transformers provides the best performance across both datasets and sets a new standard for these challenges.
