---
layout: publication
title: Generate then Retrieve Conversational Response Retrieval Using LLMs as Answer and Query Generators
authors: Abbasiantaeb Zahra, Aliannejadi Mohammad
conference: "Arxiv"
year: 2024
bibkey: abbasiantaeb2024generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19302"}
tags: ['ARXIV', 'Pretraining Methods', 'Tools']
---
CIS is a prominent area in IR which focuses on developing interactive knowledge assistants. These systems must adeptly comprehend the users information requirements within the conversational context and retrieve the relevant information. To this aim the existing approaches model the users information needs by generating a single query rewrite or a single representation of the query in the query space embedding. However to answer complex questions a single query rewrite or representation is often ineffective. To address this a system needs to do reasoning over multiple passages. In this work we propose using a generate-then-retrieve approach to improve the passage retrieval performance for complex user queries. In this approach we utilize large language models (LLMs) to (i) generate an initial answer to the users information need by doing reasoning over the context of the conversation and (ii) ground this answer to the collection. Based on the experiments our proposed approach significantly improves the retrieval performance on TREC iKAT 23 TREC CAsT 20 and 22 datasets under various setups. Also we show that grounding the LLMs answer requires more than one searchable query where an average of 3 queries outperforms human rewrites.
