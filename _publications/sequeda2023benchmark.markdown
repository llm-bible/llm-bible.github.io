---
layout: publication
title: 'A Benchmark To Understand The Role Of Knowledge Graphs On Large Language Model''s Accuracy For Question Answering On Enterprise SQL Databases'
authors: Juan Sequeda, Dean Allemang, Bryon Jacob
conference: "Arxiv"
year: 2023
bibkey: sequeda2023benchmark
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.07509'}
tags: ['Prompting', 'GPT', 'Applications', 'Model Architecture']
---
Enterprise applications of Large Language Models (LLMs) hold promise for
question answering on enterprise SQL databases. However, the extent to which
LLMs can accurately respond to enterprise questions in such databases remains
unclear, given the absence of suitable Text-to-SQL benchmarks tailored to
enterprise settings. Additionally, the potential of Knowledge Graphs (KGs) to
enhance LLM-based question answering by providing business context is not well
understood. This study aims to evaluate the accuracy of LLM-powered question
answering systems in the context of enterprise questions and SQL databases,
while also exploring the role of knowledge graphs in improving accuracy. To
achieve this, we introduce a benchmark comprising an enterprise SQL schema in
the insurance domain, a range of enterprise queries encompassing reporting to
metrics, and a contextual layer incorporating an ontology and mappings that
define a knowledge graph. Our primary finding reveals that question answering
using GPT-4, with zero-shot prompts directly on SQL databases, achieves an
accuracy of 16%. Notably, this accuracy increases to 54% when questions are
posed over a Knowledge Graph representation of the enterprise SQL database.
Therefore, investing in Knowledge Graph provides higher accuracy for LLM
powered question answering systems.
