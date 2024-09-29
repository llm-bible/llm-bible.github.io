---
layout: publication
title: LILO\: Learning Interpretable Libraries By Compressing And Documenting Code
authors: Grand Gabriel, Wong Lionel, Bowers Maddy, Olausson Theo X., Liu Muxin, Tenenbaum Joshua B., Andreas Jacob
conference: "Arxiv"
year: 2023
bibkey: grand2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19791"}
tags: ['Applications', 'Tools']
---
While large language models (LLMs) now excel at code generation a key aspect of software development is the art of refactoring consolidating code into libraries of reusable and readable programs. In this paper we introduce LILO a neurosymbolic framework that iteratively synthesizes compresses and documents code to build libraries tailored to particular problem domains. LILO combines LLM-guided program synthesis with recent algorithmic advances in automated refactoring from Stitch a symbolic compression system that efficiently identifies optimal lambda abstractions across large code corpora. To make these abstractions interpretable we introduce an auto-documentation (AutoDoc) procedure that infers natural language names and docstrings based on contextual examples of usage. In addition to improving human readability we find that AutoDoc boosts performance by helping LILOs synthesizer to interpret and deploy learned abstractions. We evaluate LILO on three inductive program synthesis benchmarks for string editing scene reasoning and graphics composition. Compared to existing neural and symbolic methods - including the state-of-the-art library learning algorithm DreamCoder - LILO solves more complex tasks and learns richer libraries that are grounded in linguistic knowledge.
