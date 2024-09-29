---
layout: publication
title: 'Question-based Retrieval Using Atomic Units For Enterprise RAG'
authors: Raina Vatsal, Gales Mark
conference: "Arxiv"
year: 2024
bibkey: raina2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12363"}
tags: ['RAG', 'Tools']
---
Enterprise retrieval augmented generation (RAG) offers a highly flexible framework for combining powerful large language models (LLMs) with internal possibly temporally changing documents. In RAG documents are first chunked. Relevant chunks are then retrieved for a user query which are passed as context to a synthesizer LLM to generate the query response. However the retrieval step can limit performance as incorrect chunks can lead the synthesizer LLM to generate a false response. This work applies a zero-shot adaptation of standard dense retrieval steps for more accurate chunk recall. Specifically a chunk is first decomposed into atomic statements. A set of synthetic questions are then generated on these atoms (with the chunk as the context). Dense retrieval involves finding the closest set of synthetic questions and associated chunks to the user query. It is found that retrieval with the atoms leads to higher recall than retrieval with chunks. Further performance gain is observed with retrieval using the synthetic questions generated over the atoms. Higher recall at the retrieval step enables higher performance of the enterprise LLM using the RAG pipeline.
