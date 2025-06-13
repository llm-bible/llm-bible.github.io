---
layout: publication
title: 'A Rag-based Institutional Assistant'
authors: Gustavo Kuratomi, Paulo Pirozelli, Fabio G. Cozman, Sarajane M. Peres
conference: "Arxiv"
year: 2025
bibkey: kuratomi2025rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13880"}
tags: ['Language Modeling', 'RAG', 'Applications', 'Model Architecture']
---
Although large language models (LLMs) demonstrate strong text generation
capabilities, they struggle in scenarios requiring access to structured
knowledge bases or specific documents, limiting their effectiveness in
knowledge-intensive tasks. To address this limitation, retrieval-augmented
generation (RAG) models have been developed, enabling generative models to
incorporate relevant document fragments into their inputs. In this paper, we
design and evaluate a RAG-based virtual assistant specifically tailored for the
University of S\~ao Paulo. Our system architecture comprises two key modules: a
retriever and a generative model. We experiment with different types of models
for both components, adjusting hyperparameters such as chunk size and the
number of retrieved documents. Our optimal retriever model achieves a Top-5
accuracy of 30%, while our most effective generative model scores 22.04%
against ground truth answers. Notably, when the correct document chunks are
supplied to the LLMs, accuracy significantly improves to 54.02%, an increase of
over 30 percentage points. Conversely, without contextual input, performance
declines to 13.68%. These findings highlight the critical role of database
access in enhancing LLM performance. They also reveal the limitations of
current semantic search methods in accurately identifying relevant documents
and underscore the ongoing challenges LLMs face in generating precise
responses.
