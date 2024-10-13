---
layout: publication
title: 'From RAG To RICHES: Retrieval Interlaced With Sequence Generation'
authors: Jain Palak, Soares Livio Baldini, Kwiatkowski Tom
conference: "Arxiv"
year: 2024
bibkey: jain2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00361"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Uncategorized']
---
We present RICHES, a novel approach that interleaves retrieval with sequence
generation tasks. RICHES offers an alternative to conventional RAG systems by
eliminating the need for separate retriever and generator. It retrieves
documents by directly decoding their contents, constrained on the corpus.
Unifying retrieval with generation allows us to adapt to diverse new tasks via
prompting alone. RICHES can work with any Instruction-tuned model, without
additional training. It provides attributed evidence, supports multi-hop
retrievals and interleaves thoughts to plan on what to retrieve next, all
within a single decoding pass of the LLM. We demonstrate the strong performance
of RICHES across ODQA tasks including attributed and multi-hop QA.
