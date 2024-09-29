---
layout: publication
title: "Exploring Italian Sentence Embeddings Properties Through Multi-tasking"
authors: Nastase Vivi, Samo Giuseppe, Jiang Chunyang, Merlo Paola
conference: "Arxiv"
year: 2024
bibkey: nastase2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06622"}
tags: ['Model Architecture', 'Pretraining Methods']
---
We investigate to what degree existing LLMs encode abstract linguistic information in Italian in a multi-task setting. We exploit curated synthetic data on a large scale -- several Blackbird Language Matrices (BLMs) problems in Italian -- and use them to study how sentence representations built using pre-trained language models encode specific syntactic and semantic information. We use a two-level architecture to model separately a compression of the sentence embeddings into a representation that contains relevant information for a task and a BLM task. We then investigate whether we can obtain compressed sentence representations that encode syntactic and semantic information relevant to several BLM tasks. While we expected that the sentence structure -- in terms of sequence of phrases/chunks -- and chunk properties could be shared across tasks performance and error analysis show that the clues for the different tasks are encoded in different manners in the sentence embeddings suggesting that abstract linguistic notions such as constituents or thematic roles does not seem to be present in the pretrained sentence embeddings.
