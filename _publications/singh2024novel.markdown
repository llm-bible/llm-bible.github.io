---
layout: publication
title: 'Chunkrag: Novel Llm-chunk Filtering Method For RAG Systems'
authors: Ishneet Sukhvinder Singh, Ritvik Aggarwal, Ibrahim Allahverdiyev, Muhammad Taha, Aslihan Akalin, Kevin Zhu, Sean O'brien
conference: "Arxiv"
year: 2024
bibkey: singh2024novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19572"}
tags: ['RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) systems using large language models
(LLMs) often generate inaccurate responses due to the retrieval of irrelevant
or loosely related information. Existing methods, which operate at the document
level, fail to effectively filter out such content. We propose LLM-driven chunk
filtering, ChunkRAG, a framework that enhances RAG systems by evaluating and
filtering retrieved information at the chunk level. Our approach employs
semantic chunking to divide documents into coherent sections and utilizes
LLM-based relevance scoring to assess each chunk's alignment with the user's
query. By filtering out less pertinent chunks before the generation phase, we
significantly reduce hallucinations and improve factual accuracy. Experiments
show that our method outperforms existing RAG models, achieving higher accuracy
on tasks requiring precise information retrieval. This advancement enhances the
reliability of RAG systems, making them particularly beneficial for
applications like fact-checking and multi-hop reasoning.
