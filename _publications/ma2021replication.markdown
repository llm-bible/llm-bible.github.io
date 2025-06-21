---
layout: publication
title: A Replication Study Of Dense Passage Retriever
authors: Xueguang Ma, Kai Sun, Ronak Pradeep, Jimmy Lin
conference: Arxiv
year: 2021
citations: 27
bibkey: ma2021replication
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.05740'}]
tags: [Tools, RAG]
---
Text retrieval using learned dense representations has recently emerged as a
promising alternative to "traditional" text retrieval using sparse bag-of-words
representations. One recent work that has garnered much attention is the dense
passage retriever (DPR) technique proposed by Karpukhin et al. (2020) for
end-to-end open-domain question answering. We present a replication study of
this work, starting with model checkpoints provided by the authors, but
otherwise from an independent implementation in our group's Pyserini IR toolkit
and PyGaggle neural text ranking library. Although our experimental results
largely verify the claims of the original paper, we arrived at two important
additional findings that contribute to a better understanding of DPR: First, it
appears that the original authors under-report the effectiveness of the BM25
baseline and hence also dense--sparse hybrid retrieval results. Second, by
incorporating evidence from the retriever and an improved answer span scoring
technique, we are able to improve end-to-end question answering effectiveness
using exactly the same models as in the original work.