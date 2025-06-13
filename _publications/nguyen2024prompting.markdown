---
layout: publication
title: 'Prompting With Phonemes: Enhancing Llms'' Multilinguality For Non-latin Script Languages'
authors: Hoang H Nguyen, Khyati Mahajan, Vikas Yadav, Julian Salazar, Philip S. Yu, Masoud Hashemi, Rishabh Maheshwary
conference: "Arxiv"
year: 2024
bibkey: nguyen2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02398"}
tags: ['Prompting', 'RAG', 'In-Context Learning', 'Reinforcement Learning']
---
Although multilingual LLMs have achieved remarkable performance across
benchmarks, we find they continue to underperform on non-Latin script languages
across contemporary LLM families. This discrepancy arises from the fact that
LLMs are pretrained with orthographic scripts, which are dominated by Latin
characters that obscure their shared phonology with non-Latin scripts. We
propose leveraging phonemic transcriptions as complementary signals to induce
script-invariant representations. Our study demonstrates that integrating
phonemic signals improves performance across both non-Latin and Latin script
languages, with a particularly significant impact on closing the performance
gap between the two. Through detailed experiments, we show that phonemic and
orthographic scripts retrieve distinct examples for in-context learning (ICL).
This motivates our proposed Mixed-ICL retrieval strategy, where further
aggregation from both leads to our significant performance improvements for
both Latin script languages (up to 12.6%) and non-Latin script languages (up to
15.1%) compared to randomized ICL retrieval.
