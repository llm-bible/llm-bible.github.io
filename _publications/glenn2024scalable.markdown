---
layout: publication
title: 'Blendsql: A Scalable Dialect For Unifying Hybrid Question Answering In Relational Algebra'
authors: Parker Glenn, Parag Pravin Dakle, Liang Wang, Preethi Raghavan
conference: "Arxiv"
year: 2024
bibkey: glenn2024scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17882"}
  - {name: "Code", url: "https://github.com/parkervg/blendsql"}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Has Code', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
Many existing end-to-end systems for hybrid question answering tasks can
often be boiled down to a "prompt-and-pray" paradigm, where the user has
limited control and insight into the intermediate reasoning steps used to
achieve the final result. Additionally, due to the context size limitation of
many transformer-based LLMs, it is often not reasonable to expect that the full
structured and unstructured context will fit into a given prompt in a zero-shot
setting, let alone a few-shot setting. We introduce BlendSQL, a superset of
SQLite to act as a unified dialect for orchestrating reasoning across both
unstructured and structured data. For hybrid question answering tasks involving
multi-hop reasoning, we encode the full decomposed reasoning roadmap into a
single interpretable BlendSQL query. Notably, we show that BlendSQL can scale
to massive datasets and improve the performance of end-to-end systems while
using 35% fewer tokens. Our code is available and installable as a package at
https://github.com/parkervg/blendsql.
