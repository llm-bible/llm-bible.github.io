---
layout: publication
title: 'ARKS: Active Retrieval In Knowledge Soup For Code Generation'
authors: Su Hongjin, Jiang Shuyang, Lai Yuhang, Wu Haoyuan, Shi Boao, Liu Che, Liu Qian, Yu Tao
conference: "Arxiv"
year: 2024
bibkey: su2024active
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12317"}
  - {name: "Code", url: "https://arks-codegen.github.io"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Training Techniques']
---
"Recently the retrieval-augmented generation (RAG) paradigm has raised much attention for its potential in incorporating external knowledge into large language models (LLMs) without further training. While widely explored in natural language applications, its utilization in code generation remains under-explored. In this paper, we introduce Active Retrieval in Knowledge Soup (ARKS), an advanced strategy for generalizing large language models for code. In contrast to relying on a single source, we construct a knowledge soup integrating web search, documentation, execution feedback, and evolved code snippets. We employ an active retrieval strategy that iteratively refines the query and updates the knowledge soup. To assess the performance of ARKS, we compile a new benchmark comprising realistic coding problems associated with frequently updated libraries and long-tail programming languages. Experimental results on ChatGPT and CodeLlama demonstrate a substantial improvement in the average execution accuracy of ARKS on LLMs. The analysis confirms the effectiveness of our proposed knowledge soup and active retrieval strategies, offering rich insights into the construction of effective retrieval-augmented code generation (RACG) pipelines. Our model, code, and data are available at https://arks-codegen.github.io."
