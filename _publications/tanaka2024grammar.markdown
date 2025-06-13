---
layout: publication
title: 'Grammar-based Game Description Generation Using Large Language Models'
authors: Tsunehiko Tanaka, Edgar Simo-serra
conference: "IEEE Transactions on Games 2024 (early access)"
year: 2024
bibkey: tanaka2024grammar
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.17404'}
  - {name: "Code", url: 'https://github.com/tsunehiko/ggdg'}
tags: ['RAG', 'Has Code', 'Tools']
---
Game Description Language (GDL) provides a standardized way to express
diverse games in a machine-readable format, enabling automated game simulation,
and evaluation. While previous research has explored game description
generation using search-based methods, generating GDL descriptions from natural
language remains a challenging task. This paper presents a novel framework that
leverages Large Language Models (LLMs) to generate grammatically accurate game
descriptions from natural language. Our approach consists of two stages: first,
we gradually generate a minimal grammar based on GDL specifications; second, we
iteratively improve the game description through grammar-guided generation. Our
framework employs a specialized parser that identifies valid subsequences and
candidate symbols from LLM responses, enabling gradual refinement of the output
to ensure grammatical correctness. Experimental results demonstrate that our
iterative improvement approach significantly outperforms baseline methods that
directly use LLM outputs. Our code is available at
https://github.com/tsunehiko/ggdg
