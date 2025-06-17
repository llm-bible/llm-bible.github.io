---
layout: publication
title: Explaining Documents' Relevance To Search Queries
authors: Razieh Rahimi, Youngwoo Kim, Hamed Zamani, James Allan
conference: Arxiv
year: 2021
citations: 22
bibkey: rahimi2021explaining
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.01314'}]
tags: [Transformer, Interpretability and Explainability, Attention Mechanism]
---
We present GenEx, a generative model to explain search results to users
beyond just showing matches between query and document words. Adding GenEx
explanations to search results greatly impacts user satisfaction and search
performance. Search engines mostly provide document titles, URLs, and snippets
for each result. Existing model-agnostic explanation methods similarly focus on
word matching or content-based features. However, a recent user study shows
that word matching features are quite obvious to users and thus of slight
value. GenEx explains a search result by providing a terse description for the
query aspect covered by that result. We cast the task as a sequence
transduction problem and propose a novel model based on the Transformer
architecture. To represent documents with respect to the given queries and yet
not generate the queries themselves as explanations, two query-attention layers
and masked-query decoding are added to the Transformer architecture. The model
is trained without using any human-generated explanations. Training data are
instead automatically constructed to ensure a tolerable noise level and a
generalizable learned model. Experimental evaluation shows that our explanation
models significantly outperform the baseline models. Evaluation through user
studies also demonstrates that our explanation model generates short yet useful
explanations.