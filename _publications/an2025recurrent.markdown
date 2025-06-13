---
layout: publication
title: 'LCIRC: A Recurrent Compression Approach For Efficient Long-form Context And Query Dependent Modeling In Llms'
authors: Sumin An, Junyoung Sung, Wonpyo Park, Chanjun Park, Paul Hongsuck Seo
conference: "Arxiv"
year: 2025
bibkey: an2025recurrent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06139"}
tags: ['Training Techniques']
---
While large language models (LLMs) excel in generating coherent and contextually rich outputs, their capacity to efficiently handle long-form contexts is limited by fixed-length position embeddings. Additionally, the computational cost of processing long sequences increases quadratically, making it challenging to extend context length. To address these challenges, we propose Long-form Context Injection with Recurrent Compression (LCIRC), a method that enables the efficient processing long-form sequences beyond the model's length limit through recurrent compression without retraining the entire model. We further introduce query dependent context modeling, which selectively compresses query-relevant information, ensuring that the model retains the most pertinent content. Our empirical results demonstrate that Query Dependent LCIRC (QD-LCIRC) significantly improves LLM's ability to manage extended contexts, making it well-suited for tasks that require both comprehensive context understanding and query relevance.
