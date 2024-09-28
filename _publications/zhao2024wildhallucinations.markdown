---
layout: publication
title: WildHallucinations Evaluating Long-form Factuality in LLMs with Real-World Entity Queries
authors: Zhao Wenting, Goyal Tanya, Chiu Yu Ying, Jiang Liwei, Newman Benjamin, Ravichander Abhilasha, Chandu Khyathi, Bras Ronan Le, Cardie Claire, Deng Yuntian, Choi Yejin
conference: "Arxiv"
year: 2024
bibkey: zhao2024wildhallucinations
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17468"}
tags: ['ARXIV', 'Ethics And Bias', 'LLM', 'Reinforcement Learning', 'Tools']
---
While hallucinations of large language models (LLMs) prevail as a major challenge existing evaluation benchmarks on factuality do not cover the diverse domains of knowledge that the real-world users of LLMs seek information about. To bridge this gap we introduce WildHallucinations a benchmark that evaluates factuality. It does so by prompting LLMs to generate information about entities mined from user-chatbot conversations in the wild. These generations are then automatically fact-checked against a systematically curated knowledge source collected from web search. Notably half of these real-world entities do not have associated Wikipedia pages. We evaluate 118785 generations from 15 LLMs on 7919 entities. We find that LLMs consistently hallucinate more on entities without Wikipedia pages and exhibit varying hallucination rates across different domains. Finally given the same base models adding a retrieval component only slightly reduces hallucinations but does not eliminate hallucinations.
