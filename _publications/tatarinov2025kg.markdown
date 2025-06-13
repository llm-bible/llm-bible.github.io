---
layout: publication
title: 'Kg-qagen: A Knowledge-graph-based Framework For Systematic Question Generation And Long-context LLM Evaluation'
authors: Nikita Tatarinov, Vidhyakshaya Kannan, Haricharana Srinivasa, Arnav Raj, Harpreet Singh Anand, Varun Singh, Aditya Luthra, Ravij Lade, Agam Shah, Sudheer Chava
conference: "Arxiv"
year: 2025
bibkey: tatarinov2025kg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12495"}
tags: ['RAG', 'Tools']
---
The increasing context length of modern language models has created a need for evaluating their ability to retrieve and process information across extensive documents. While existing benchmarks test long-context capabilities, they often lack a structured way to systematically vary question complexity. We introduce KG-QAGen (Knowledge-Graph-based Question-Answer Generation), a framework that (1) extracts QA pairs at multiple complexity levels (2) by leveraging structured representations of financial agreements (3) along three key dimensions -- multi-hop retrieval, set operations, and answer plurality -- enabling fine-grained assessment of model performance across controlled difficulty levels. Using this framework, we construct a dataset of 20,139 QA pairs (the largest number among the long-context benchmarks) and open-source a part of it. We evaluate 13 proprietary and open-source LLMs and observe that even the best-performing models are struggling with set-based comparisons and multi-hop logical inference. Our analysis reveals systematic failure modes tied to semantic misinterpretation and inability to handle implicit relations.
