---
layout: publication
title: 'Reducing Hallucinations In Language Model-based SPARQL Query Generation Using Post-generation Memory Retrieval'
authors: Aditya Sharma, Luis Lara, Christopher J. Pal, Amal Zouaq
conference: "Arxiv"
year: 2025
bibkey: sharma2025reducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13369"}
tags: ['Tools', 'Applications', 'Reinforcement Learning']
---
The ability to generate SPARQL queries from natural language questions is crucial for ensuring efficient and accurate retrieval of structured data from knowledge graphs (KG). While large language models (LLMs) have been widely adopted for SPARQL query generation, they are often susceptible to hallucinations and out-of-distribution errors when producing KG elements like Uniform Resource Identifiers (URIs) based on internal parametric knowledge. This often results in content that appears plausible but is factually incorrect, posing significant challenges for their use in real-world information retrieval (IR) applications. This has led to increased research aimed at detecting and mitigating such errors. In this paper, we introduce PGMR (Post-Generation Memory Retrieval), a modular framework that incorporates a non-parametric memory module to retrieve KG elements and enhance LLM-based SPARQL query generation. Our experimental results indicate that PGMR consistently delivers strong performance across diverse datasets, data distributions, and LLMs. Notably, PGMR significantly mitigates URI hallucinations, nearly eliminating the problem in several scenarios.
