---
layout: publication
title: 'Toolfactory: Automating Tool Generation By Leveraging LLM To Understand REST API Documentations'
authors: Xinyi Brandeis University Ni, Qiuyang Brandeis University Wang, Yukun Brandeis University Zhang, Pengyu Brandeis University Hong
conference: "Arxiv"
year: 2025
bibkey: ni2025automating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.16945'}
tags: ['Reinforcement Learning', 'Agentic', 'RAG', 'Tools']
---
LLM-based tool agents offer natural language interfaces, enabling users to
seamlessly interact with computing services. While REST APIs are valuable
resources for building such agents, they must first be transformed into
AI-compatible tools. Automatically generating AI-compatible tools from REST API
documents can greatly streamline tool agent development and minimize user
learning curves. However, API documentation often suffers from a lack of
standardization, inconsistent schemas, and incomplete information. To address
these issues, we developed \textbf\{ToolFactory\}, an open-source pipeline for
automating tool generation from unstructured API documents. To enhance the
reliability of the developed tools, we implemented an evaluation method to
diagnose errors. Furthermore, we built a knowledge base of verified tools,
which we leveraged to infer missing information from poorly documented APIs. We
developed the API Extraction Benchmark, comprising 167 API documents and 744
endpoints in various formats, and designed a JSON schema to annotate them. This
annotated dataset was utilized to train and validate ToolFactory. The
experimental results highlight the effectiveness of ToolFactory. We also
demonstrated ToolFactory by creating a domain-specific AI agent for
glycomaterials research. ToolFactory exhibits significant potential for
facilitating the seamless integration of scientific REST APIs into AI
workflows.
