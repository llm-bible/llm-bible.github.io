---
layout: publication
title: 'Treehop: Generate And Filter Next Query Embeddings Efficiently For Multi-hop Question Answering'
authors: Zhonghao Li, Kunpeng Zhang, Jinghuai Ou, Shuliang Liu, Xuming Hu
conference: "Arxiv"
year: 2025
bibkey: li2025generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20114"}
  - {name: "Code", url: "https://github.com/allen-li1231/TreeHop-RAG"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Has Code']
---
Retrieval-augmented generation (RAG) systems face significant challenges in
multi-hop question answering (MHQA), where complex queries require synthesizing
information across multiple document chunks. Existing approaches typically rely
on iterative LLM-based query rewriting and routing, resulting in high
computational costs due to repeated LLM invocations and multi-stage processes.
To address these limitations, we propose TreeHop, an embedding-level framework
without the need for LLMs in query refinement. TreeHop dynamically updates
query embeddings by fusing semantic information from prior queries and
retrieved documents, enabling iterative retrieval through embedding-space
operations alone. This method replaces the traditional
"Retrieve-Rewrite-Vectorize-Retrieve" cycle with a streamlined
"Retrieve-Embed-Retrieve" loop, significantly reducing computational overhead.
Moreover, a rule-based stop criterion is introduced to further prune redundant
retrievals, balancing efficiency and recall rate. Experimental results show
that TreeHop rivals advanced RAG methods across three open-domain MHQA
datasets, achieving comparable performance with only 5%-0.4% of the model
parameter size and reducing the query latency by approximately 99% compared to
concurrent approaches. This makes TreeHop a faster and more cost-effective
solution for deployment in a range of knowledge-intensive applications. For
reproducibility purposes, codes and data are available here:
https://github.com/allen-li1231/TreeHop-RAG.
