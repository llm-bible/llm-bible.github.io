---
layout: publication
title: 'Modeling Context In Answer Sentence Selection Systems On A Latency Budget'
authors: Rujun Han, Luca Soldaini, Alessandro Moschitti
conference: "Arxiv"
year: 2021
bibkey: han2021modeling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.12093"}
tags: ['Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Answer Sentence Selection (AS2) is an efficient approach for the design of
open-domain Question Answering (QA) systems. In order to achieve low latency,
traditional AS2 models score question-answer pairs individually, ignoring any
information from the document each potential answer was extracted from. In
contrast, more computationally expensive models designed for machine reading
comprehension tasks typically receive one or more passages as input, which
often results in better accuracy. In this work, we present an approach to
efficiently incorporate contextual information in AS2 models. For each answer
candidate, we first use unsupervised similarity techniques to extract relevant
sentences from its source document, which we then feed into an efficient
transformer architecture fine-tuned for AS2. Our best approach, which leverages
a multi-way attention architecture to efficiently encode context, improves 6%
to 11% over noncontextual state of the art in AS2 with minimal impact on system
latency. All experiments in this work were conducted in English.
