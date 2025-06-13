---
layout: publication
title: 'Qa-expand: Multi-question Answer Generation For Enhanced Query Expansion In Information Retrieval'
authors: Wonduk Seo, Seunghyun Lee
conference: "Arxiv"
year: 2025
bibkey: seo2025qa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08557"}
tags: ['Tools', 'Prompting', 'Applications']
---
Query expansion is widely used in Information Retrieval (IR) to improve
search outcomes by enriching queries with additional contextual information.
Although recent Large Language Model (LLM) based methods generate
pseudo-relevant content and expanded terms via multiple prompts, they often
yield repetitive, narrow expansions that lack the diverse context needed to
retrieve all relevant information. In this paper, we introduce QA-Expand, a
novel and effective framework for query expansion. It first generates multiple
relevant questions from the initial query and subsequently produces
corresponding pseudo-answers as surrogate documents. A feedback model further
rewrites and filters these answers to ensure only the most informative
augmentations are incorporated. Extensive experiments on benchmarks such as
BEIR and TREC demonstrate that QA-Expand enhances retrieval performance by up
to 13% over state-of-the-art methods, offering a robust solution for modern
retrieval challenges.
