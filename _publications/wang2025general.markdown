---
layout: publication
title: 'General Table Question Answering Via Answer-formula Joint Generation'
authors: Zhongyuan Wang, Richong Zhang, Zhijie Nie
conference: "Arxiv"
year: 2025
bibkey: wang2025general
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.12345'}
tags: ['Prompting', 'Applications', 'Tools']
---
Advanced table question answering (TableQA) methods prompt large language models (LLMs) to generate answer text, SQL query, Python code, or custom operations, which impressively improve the complex reasoning problems in the TableQA task. However, these methods lack the versatility to cope with specific question types or table structures. In contrast, the Spreadsheet Formula, the widely used and well-defined operation language for tabular data, has not been thoroughly explored to solve TableQA. In this paper, we first attempt to use the Formula as the executable representation for solving complex reasoning on tables with different structures. Specifically, we construct \texttt\{FromulaQA\}, a large Formula-annotated TableQA dataset from existing datasets. In addition, we propose \texttt\{TabAF\}, a general table answering framework to solve multiple types of tasks over multiple types of tables simultaneously. Unlike existing methods, \texttt\{TabAF\} decodes answers and Formulas with a single LLM backbone, demonstrating great versatility and generalization. \texttt\{TabAF\} based on Llama3.1-70B achieves new state-of-the-art performance on the WikiTableQuestion, HiTab, and TabFact.
