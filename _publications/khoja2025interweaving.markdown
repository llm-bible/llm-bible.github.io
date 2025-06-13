---
layout: publication
title: 'Weaver: Interweaving SQL And LLM For Table Reasoning'
authors: Rohit Khoja, Devanshu Gupta, Yanjie Fu, Dan Roth, Vivek Gupta
conference: "Arxiv"
year: 2025
bibkey: khoja2025interweaving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18961"}
tags: ['RAG', 'Applications', 'Tools']
---
Querying tables with unstructured data is challenging due to the presence of text (or image), either embedded in the table or in external paragraphs, which traditional SQL struggles to process, especially for tasks requiring semantic reasoning. While Large Language Models (LLMs) excel at understanding context, they face limitations with long input sequences. Existing approaches that combine SQL and LLMs typically rely on rigid, predefined work-flows, limiting their adaptability to complex queries. To address these issues, we introduce Weaver , a modular pipeline that dynamically integrates SQL and LLMs for table-based question answering (TableQA). Weaver generates a flexible, step-by-step plan that combines SQL for structured data retrieval with LLMs for semantic processing. By decomposing complex queries into manageable subtasks, Weaver improves accuracy and generalization. Our experiments show that Weaver consistently outperforms state-of-the-art methods across four TableQA datasets, reducing both API calls and error rates.
