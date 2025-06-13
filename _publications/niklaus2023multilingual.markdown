---
layout: publication
title: 'Multilegalpile: A 689GB Multilingual Legal Corpus'
authors: Joel Niklaus, Veton Matoshi, Matthias Stürmer, Ilias Chalkidis, Daniel E. Ho
conference: "Arxiv"
year: 2023
bibkey: niklaus2023multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.02069'}
tags: ['Training Techniques', 'BERT', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large, high-quality datasets are crucial for training Large Language Models
(LLMs). However, so far, there are few datasets available for specialized
critical domains such as law and the available ones are often only for the
English language. We curate and release MultiLegalPile, a 689GB corpus in 24
languages from 17 jurisdictions. The MultiLegalPile corpus, which includes
diverse legal data sources with varying licenses, allows for pretraining NLP
models under fair use, with more permissive licenses for the Eurlex Resources
and Legal mC4 subsets. We pretrain two RoBERTa models and one Longformer
multilingually, and 24 monolingual models on each of the language-specific
subsets and evaluate them on LEXTREME. Additionally, we evaluate the English
and multilingual models on LexGLUE. Our multilingual models set a new SotA on
LEXTREME and our English models on LexGLUE. We release the dataset, the trained
models, and all of the code under the most open possible licenses.
