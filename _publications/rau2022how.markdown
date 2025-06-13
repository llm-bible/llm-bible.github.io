---
layout: publication
title: 'How Different Are Pre-trained Transformers For Text Ranking?'
authors: David Rau, Jaap Kamps
conference: "Arxiv"
year: 2022
bibkey: rau2022how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2204.07233'}
tags: ['Transformer', 'RAG', 'BERT', 'Model Architecture', 'Pretraining Methods']
---
In recent years, large pre-trained transformers have led to substantial gains
in performance over traditional retrieval models and feedback approaches.
However, these results are primarily based on the MS Marco/TREC Deep Learning
Track setup, with its very particular setup, and our understanding of why and
how these models work better is fragmented at best. We analyze effective
BERT-based cross-encoders versus traditional BM25 ranking for the passage
retrieval task where the largest gains have been observed, and investigate two
main questions. On the one hand, what is similar? To what extent does the
neural ranker already encompass the capacity of traditional rankers? Is the
gain in performance due to a better ranking of the same documents (prioritizing
precision)? On the other hand, what is different? Can it retrieve effectively
documents missed by traditional systems (prioritizing recall)? We discover
substantial differences in the notion of relevance identifying strengths and
weaknesses of BERT that may inspire research for future improvement. Our
results contribute to our understanding of (black-box) neural rankers relative
to (well-understood) traditional rankers, help understand the particular
experimental setting of MS-Marco-based test collections.
