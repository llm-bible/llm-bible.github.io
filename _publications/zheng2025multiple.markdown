---
layout: publication
title: 'Multiple Abstraction Level Retrieve Augment Generation'
authors: Zheng Zheng, Xinyi Ni, Pengyu Hong
conference: "Arxiv"
year: 2025
bibkey: zheng2025multiple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.16952"}
tags: ['RAG', 'Reinforcement Learning']
---
A Retrieval-Augmented Generation (RAG) model powered by a large language
model (LLM) provides a faster and more cost-effective solution for adapting to
new data and knowledge. It also delivers more specialized responses compared to
pre-trained LLMs. However, most existing approaches rely on retrieving
prefix-sized chunks as references to support question-answering (Q/A). This
approach is often deployed to address information needs at a single level of
abstraction, as it struggles to generate answers across multiple levels of
abstraction. In an RAG setting, while LLMs can summarize and answer questions
effectively when provided with sufficient details, retrieving excessive
information often leads to the 'lost in the middle' problem and exceeds token
limitations. We propose a novel RAG approach that uses chunks of multiple
abstraction levels (MAL), including multi-sentence-level, paragraph-level,
section-level, and document-level. The effectiveness of our approach is
demonstrated in an under-explored scientific domain of Glycoscience. Compared
to traditional single-level RAG approaches, our approach improves AI evaluated
answer correctness of Q/A by 25.739% on Glyco-related papers.
