---
layout: publication
title: 'Say Less, Mean More: Leveraging Pragmatics In Retrieval-augmented Generation'
authors: Haris Riaz, Ellen Riloff, Mihai Surdeanu
conference: "Arxiv"
year: 2025
bibkey: riaz2025say
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17839"}
tags: ['RAG', 'Tools', 'Applications']
---
We propose a simple, unsupervised method that injects pragmatic principles in
retrieval-augmented generation (RAG) frameworks such as Dense Passage Retrieval
to enhance the utility of retrieved contexts. Our approach first identifies
which sentences in a pool of documents retrieved by RAG are most relevant to
the question at hand, cover all the topics addressed in the input question and
no more, and then highlights these sentences within their context, before they
are provided to the LLM, without truncating or altering the context in any
other way. We show that this simple idea brings consistent improvements in
experiments on three question answering tasks (ARC-Challenge, PubHealth and
PopQA) using five different LLMs. It notably enhances relative accuracy by up
to 19.7% on PubHealth and 10% on ARC-Challenge compared to a conventional RAG
system.
