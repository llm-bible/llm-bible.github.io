---
layout: publication
title: 'Generate Then Retrieve: Conversational Response Retrieval Using Llms As Answer And Query Generators'
authors: Abbasiantaeb Zahra, Aliannejadi Mohammad
conference: "Arxiv"
year: 2024
bibkey: abbasiantaeb2024generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19302"}
tags: ['RAG', 'Uncategorized']
---
CIS is a prominent area in IR which focuses on developing interactive knowledge assistants. These systems must adeptly comprehend the user's information requirements within the conversational context and retrieve the relevant information. To this aim, the existing approaches model the user's information needs by generating a single query rewrite or a single representation of the query in the query space embedding. However, to answer complex questions, a single query rewrite or representation is often ineffective. To address this, a system needs to do reasoning over multiple passages. In this work, we propose using a generate-then-retrieve approach to improve the passage retrieval performance for complex user queries. In this approach, we utilize large language models (LLMs) to (i) generate an initial answer to the user's information need by doing reasoning over the context of the conversation, and (ii) ground this answer to the collection. Based on the experiments, our proposed approach significantly improves the retrieval performance on TREC iKAT 23, TREC CAsT 20 and 22 datasets, under various setups. Also, we show that grounding the LLM's answer requires more than one searchable query, where an average of 3 queries outperforms human rewrites.
