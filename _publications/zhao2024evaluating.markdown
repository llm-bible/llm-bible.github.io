---
layout: publication
title: 'Wildhallucinations: Evaluating Long-form Factuality In Llms With Real-world Entity Queries'
authors: Wenting Zhao, Tanya Goyal, Yu Ying Chiu, Liwei Jiang, Benjamin Newman, Abhilasha Ravichander, Khyathi Chandu, Ronan Le Bras, Claire Cardie, Yuntian Deng, Yejin Choi
conference: "Arxiv"
year: 2024
bibkey: zhao2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.17468'}
tags: ['Reinforcement Learning', 'Prompting']
---
While hallucinations of large language models (LLMs) prevail as a major
challenge, existing evaluation benchmarks on factuality do not cover the
diverse domains of knowledge that the real-world users of LLMs seek information
about. To bridge this gap, we introduce WildHallucinations, a benchmark that
evaluates factuality. It does so by prompting LLMs to generate information
about entities mined from user-chatbot conversations in the wild. These
generations are then automatically fact-checked against a systematically
curated knowledge source collected from web search. Notably, half of these
real-world entities do not have associated Wikipedia pages. We evaluate 118,785
generations from 15 LLMs on 7,919 entities. We find that LLMs consistently
hallucinate more on entities without Wikipedia pages and exhibit varying
hallucination rates across different domains. Finally, given the same base
models, adding a retrieval component only slightly reduces hallucinations but
does not eliminate hallucinations.
