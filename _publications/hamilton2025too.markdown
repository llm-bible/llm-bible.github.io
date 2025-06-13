---
layout: publication
title: 'Too Long, Didn''t Model: Decomposing LLM Long-context Understanding With Novels'
authors: Sil Hamilton, Rebecca M. M. Hicke, Matthew Wilkens, David Mimno
conference: "Arxiv"
year: 2025
bibkey: hamilton2025too
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14925'}
tags: ['Reinforcement Learning']
---
Although the context length of large language models (LLMs) has increased to millions of tokens, evaluating their effectiveness beyond needle-in-a-haystack approaches has proven difficult. We argue that novels provide a case study of subtle, complicated structure and long-range semantic dependencies often over 128k tokens in length. Inspired by work on computational novel analysis, we release the Too Long, Didn't Model (TLDM) benchmark, which tests a model's ability to report plot summary, storyworld configuration, and elapsed narrative time. We find that none of seven tested frontier LLMs retain stable understanding beyond 64k tokens. Our results suggest language model developers must look beyond "lost in the middle" benchmarks when evaluating model performance in complex long-context scenarios. To aid in further development we release the TLDM benchmark together with reference code and data.
