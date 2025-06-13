---
layout: publication
title: 'On Mechanistic Circuits For Extractive Question-answering'
authors: Samyadeep Basu, Vlad Morariu, Zichao Wang, Ryan Rossi, Cherry Zhao, Soheil Feizi, Varun Manjunatha
conference: "Arxiv"
year: 2025
bibkey: basu2025mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08059"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Applications', 'Attention Mechanism']
---
Large language models are increasingly used to process documents and
facilitate question-answering on them. In our paper, we extract mechanistic
circuits for this real-world language modeling task: context-augmented language
modeling for extractive question-answering (QA) tasks and understand the
potential benefits of circuits towards downstream applications such as data
attribution to context information. We extract circuits as a function of
internal model components (e.g., attention heads, MLPs) using causal mediation
analysis techniques. Leveraging the extracted circuits, we first understand the
interplay between the model's usage of parametric memory and retrieved context
towards a better mechanistic understanding of context-augmented language
models. We then identify a small set of attention heads in our circuit which
performs reliable data attribution by default, thereby obtaining attribution
for free in just the model's forward pass. Using this insight, we then
introduce ATTNATTRIB, a fast data attribution algorithm which obtains
state-of-the-art attribution results across various extractive QA benchmarks.
Finally, we show the possibility to steer the language model towards answering
from the context, instead of the parametric memory by using the attribution
from ATTNATTRIB as an additional signal during the forward pass. Beyond
mechanistic understanding, our paper provides tangible applications of circuits
in the form of reliable data attribution and model steering.
