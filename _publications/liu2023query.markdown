---
layout: publication
title: 'Query-utterance Attention With Joint Modeling For Query-focused Meeting Summarization'
authors: Xingxian Liu, Bin Duan, Bo Xiao, Yajing Xu
conference: "Arxiv"
year: 2023
bibkey: liu2023query
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2303.04487'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Applications', 'Tools', 'Pretraining Methods']
---
Query-focused meeting summarization (QFMS) aims to generate summaries from
meeting transcripts in response to a given query. Previous works typically
concatenate the query with meeting transcripts and implicitly model the query
relevance only at the token level with attention mechanism. However, due to the
dilution of key query-relevant information caused by long meeting transcripts,
the original transformer-based model is insufficient to highlight the key parts
related to the query. In this paper, we propose a query-aware framework with
joint modeling token and utterance based on Query-Utterance Attention. It
calculates the utterance-level relevance to the query with a dense retrieval
module. Then both token-level query relevance and utterance-level query
relevance are combined and incorporated into the generation process with
attention mechanism explicitly. We show that the query relevance of different
granularities contributes to generating a summary more related to the query.
Experimental results on the QMSum dataset show that the proposed model achieves
new state-of-the-art performance.
