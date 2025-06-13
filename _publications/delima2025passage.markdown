---
layout: publication
title: 'Passage Query Methods For Retrieval And Reranking In Conversational Agents'
authors: Victor De Lima, Grace Hui Yang
conference: "Arxiv"
year: 2025
bibkey: delima2025passage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00238"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'RAG', 'GPT', 'Applications']
---
This paper presents our approach to the TREC Interactive Knowledge Assistance
Track (iKAT), which focuses on improving conversational information-seeking
(CIS) systems. While recent advancements in CIS have improved conversational
agents' ability to assist users, significant challenges remain in understanding
context and retrieving relevant documents across domains and dialogue turns. To
address these issues, we extend the Generate-Retrieve-Generate pipeline by
developing passage queries (PQs) that align with the target document's expected
format to improve query-document matching during retrieval. We propose two
variations of this approach: Weighted Reranking and Short and Long Passages.
Each method leverages a Meta Llama model for context understanding and
generating queries and responses. Passage ranking evaluation results show that
the Short and Long Passages approach outperformed the organizers' baselines,
performed best among Llama-based systems in the track, and achieved results
comparable to GPT-4-based systems. These results indicate that the method
effectively balances efficiency and performance. Findings suggest that PQs
improve semantic alignment with target documents and demonstrate their
potential to improve multi-turn dialogue systems.
