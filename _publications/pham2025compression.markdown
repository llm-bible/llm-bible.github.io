---
layout: publication
title: 'CLIPPER: Compression Enables Long-context Synthetic Data Generation'
authors: Chau Minh Pham, Yapei Chang, Mohit Iyyer
conference: "Arxiv"
year: 2025
bibkey: pham2025compression
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14854"}
tags: ['Uncategorized']
---
LLM developers are increasingly reliant on synthetic data, but generating
high-quality data for complex long-context reasoning tasks remains challenging.
We introduce CLIPPER, a compression-based approach for generating synthetic
data tailored to narrative claim verification - a task that requires reasoning
over a book to verify a given claim. Instead of generating claims directly from
the raw text of the book, which results in artifact-riddled claims, CLIPPER
first compresses the book into chapter outlines and book summaries and then
uses these intermediate representations to generate complex claims and
corresponding chain-of-thoughts. Compared to naive approaches, CLIPPER produces
claims that are more valid, grounded, and complex. Using CLIPPER, we construct
a dataset of 19K synthetic book claims paired with their source texts and
chain-of-thought reasoning, and use it to fine-tune three open-weight models.
Our best model achieves breakthrough results on narrative claim verification
(from 28% to 76% accuracy on our test set) and sets a new state-of-the-art for
sub-10B models on the NoCha leaderboard. Further analysis shows that our models
generate more detailed and grounded chain-of-thought reasoning while also
improving performance on other narrative understanding tasks (e.g.,
NarrativeQA).
