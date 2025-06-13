---
layout: publication
title: 'RAISE: Reasoning Agent For Interactive SQL Exploration'
authors: Fernando Granado, Roberto Lotufo, Jayr Pereira
conference: "Arxiv"
year: 2025
bibkey: granado2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01273"}
tags: ['Fine-Tuning', 'RAG', 'Agentic', 'Tools']
---
Recent advances in large language models (LLMs) have propelled research in natural language interfaces to databases. However, most state-of-the-art text-to-SQL systems still depend on complex, multi-stage pipelines. This work proposes a novel agentic framework that unifies schema linking, query generation, and iterative refinement within a single, end-to-end component. By leveraging the intrinsic reasoning abilities of LLMs, our method emulates how humans answer questions when working with unfamiliar databases: understanding the data by formulating hypotheses, running dynamic queries to validate them, reasoning over the results, and revising outputs based on observed results. Crucially, our approach introduces a new strategy for scaling test-time computation in text-to-SQL: we scale the depth of interactive database exploration and reflection. This shift enables the model to allocate computation dynamically to better understand the data, especially useful in ambiguous and underspecified scenarios. Our experiments show that it improved the Execution Accuracy (EX) from 44.8% to 56.5% on the challenging BIRD dataset using DeepSeek-R1-Distill-Llama-70B. Furthermore, when equipped with steps to add more diversity to the answers, our agent achieves a Best-of-N accuracy of 81.8% with 8 rounds of candidate generation, rivaling the 82.79% achieved by the top-ranked published solution, while reducing engineering complexity. These findings position our unified framework as a promising alternative for building natural language interfaces to databases.
