---
layout: publication
title: From Zero To Hero On The Limitations Of Zero45;shot Cross45;lingual Transfer With Multilingual Transformers
authors: Lauscher Anne, Ravishankar Vinit, Vulić Ivan, Glavaš Goran
conference: "Arxiv"
year: 2020
bibkey: lauscher2020from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.00633"}
tags: ['BERT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Massively multilingual transformers pretrained with language modeling objectives (e.g. mBERT XLM45;R) have become a de facto default transfer paradigm for zero45;shot cross45;lingual transfer in NLP offering unmatched transfer performance. Current downstream evaluations however verify their efficacy predominantly in transfer settings involving languages with sufficient amounts of pretraining data and with lexically and typologically close languages. In this work we analyze their limitations and show that cross45;lingual transfer via massively multilingual transformers much like transfer via cross45;lingual word embeddings is substantially less effective in resource45;lean scenarios and for distant languages. Our experiments encompassing three lower45;level tasks (POS tagging dependency parsing NER) as well as two high45;level semantic tasks (NLI QA) empirically correlate transfer performance with linguistic similarity between the source and target languages but also with the size of pretraining corpora of target languages. We also demonstrate a surprising effectiveness of inexpensive few45;shot transfer (i.e. fine45;tuning on a few target45;language instances after fine45;tuning in the source) across the board. This suggests that additional research efforts should be invested to reach beyond the limiting zero45;shot conditions.
