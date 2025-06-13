---
layout: publication
title: 'Structured Context And High-coverage Grammar For Conversational Question Answering Over Knowledge Graphs'
authors: Pierre Marion, Paweł Krzysztof Nowak, Francesco Piccinno
conference: "Arxiv"
year: 2021
bibkey: marion2021structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.00269"}
tags: ['Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
We tackle the problem of weakly-supervised conversational Question Answering
over large Knowledge Graphs using a neural semantic parsing approach. We
introduce a new Logical Form (LF) grammar that can model a wide range of
queries on the graph while remaining sufficiently simple to generate
supervision data efficiently. Our Transformer-based model takes a JSON-like
structure as input, allowing us to easily incorporate both Knowledge Graph and
conversational contexts. This structured input is transformed to lists of
embeddings and then fed to standard attention layers. We validate our approach,
both in terms of grammar coverage and LF execution accuracy, on two publicly
available datasets, CSQA and ConvQuestions, both grounded in Wikidata. On CSQA,
our approach increases the coverage from \\(80%\\) to \\(96.2%\\), and the LF
execution accuracy from \\(70.6%\\) to \\(75.6%\\), with respect to previous
state-of-the-art results. On ConvQuestions, we achieve competitive results with
respect to the state-of-the-art.
