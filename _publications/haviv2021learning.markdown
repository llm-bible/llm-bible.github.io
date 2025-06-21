---
layout: publication
title: 'Bertese: Learning To Speak To BERT'
authors: Adi Haviv, Jonathan Berant, Amir Globerson
conference: Arxiv
year: 2021
citations: 29
bibkey: haviv2021learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.05327'}]
tags: [RAG, Reinforcement Learning, BERT]
---
Large pre-trained language models have been shown to encode large amounts of
world and commonsense knowledge in their parameters, leading to substantial
interest in methods for extracting that knowledge. In past work, knowledge was
extracted by taking manually-authored queries and gathering paraphrases for
them using a separate pipeline. In this work, we propose a method for
automatically rewriting queries into "BERTese", a paraphrase query that is
directly optimized towards better knowledge extraction. To encourage meaningful
rewrites, we add auxiliary loss functions that encourage the query to
correspond to actual language tokens. We empirically show our approach
outperforms competing baselines, obviating the need for complex pipelines.
Moreover, BERTese provides some insight into the type of language that helps
language models perform knowledge extraction.