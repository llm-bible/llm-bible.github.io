---
layout: publication
title: 'On The Effectiveness Of Pretrained Models For API Learning'
authors: Mohammad Abdul Hadi, Imam Nur Bani Yusuf, Ferdian Thung, Kien Gia Luong, Jiang Lingxiao, Fatemeh H. Fard, David Lo
conference: "30th International Conference on Program Comprehension (ICPC 22) May 16--17 2022 Virtual Event USA"
year: 2022
bibkey: hadi2022effectiveness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.03498"}
tags: ['Transformer', 'Tools', 'Applications', 'Model Architecture', 'Tokenization', 'Pretraining Methods']
---
Developers frequently use APIs to implement certain functionalities, such as
parsing Excel Files, reading and writing text files line by line, etc.
Developers can greatly benefit from automatic API usage sequence generation
based on natural language queries for building applications in a faster and
cleaner manner. Existing approaches utilize information retrieval models to
search for matching API sequences given a query or use RNN-based
encoder-decoder to generate API sequences. As it stands, the first approach
treats queries and API names as bags of words. It lacks deep comprehension of
the semantics of the queries. The latter approach adapts a neural language
model to encode a user query into a fixed-length context vector and generate
API sequences from the context vector.
  We want to understand the effectiveness of recent Pre-trained Transformer
based Models (PTMs) for the API learning task. These PTMs are trained on large
natural language corpora in an unsupervised manner to retain contextual
knowledge about the language and have found success in solving similar Natural
Language Processing (NLP) problems. However, the applicability of PTMs has not
yet been explored for the API sequence generation task. We use a dataset that
contains 7 million annotations collected from GitHub to evaluate the PTMs
empirically. This dataset was also used to assess previous approaches. Based on
our results, PTMs generate more accurate API sequences and outperform other
related methods by around 11%. We have also identified two different
tokenization approaches that can contribute to a significant boost in PTMs'
performance for the API sequence generation task.
