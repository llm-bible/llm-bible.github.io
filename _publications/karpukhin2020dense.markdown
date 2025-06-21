---
layout: publication
title: Dense Passage Retrieval For Open-domain Question Answering
authors: Vladimir Karpukhin et al.
conference: Arxiv
year: 2020
citations: 910
bibkey: karpukhin2020dense
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.04906'}]
tags: [Tools, RAG]
---
Open-domain question answering relies on efficient passage retrieval to
select candidate contexts, where traditional sparse vector space models, such
as TF-IDF or BM25, are the de facto method. In this work, we show that
retrieval can be practically implemented using dense representations alone,
where embeddings are learned from a small number of questions and passages by a
simple dual-encoder framework. When evaluated on a wide range of open-domain QA
datasets, our dense retriever outperforms a strong Lucene-BM25 system largely
by 9%-19% absolute in terms of top-20 passage retrieval accuracy, and helps our
end-to-end QA system establish new state-of-the-art on multiple open-domain QA
benchmarks.