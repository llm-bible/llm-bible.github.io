---
layout: publication
title: 'RAG Playground: A Framework For Systematic Evaluation Of Retrieval Strategies And Prompt Engineering In RAG Systems'
authors: Ioannis Yiannis Papadimitriou, Ilias Yiannis Gialampoukidis, Stefanos Yiannis Vrochidis, Yiannis Ioannis, Kompatsiaris
conference: "Arxiv"
year: 2024
bibkey: papadimitriou2024rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12322"}
tags: ['RAG', 'Agentic', 'Prompting', 'Tools']
---
We present RAG Playground, an open-source framework for systematic evaluation
of Retrieval-Augmented Generation (RAG) systems. The framework implements and
compares three retrieval approaches: naive vector search, reranking, and hybrid
vector-keyword search, combined with ReAct agents using different prompting
strategies. We introduce a comprehensive evaluation framework with novel
metrics and provide empirical results comparing different language models
(Llama 3.1 and Qwen 2.5) across various retrieval configurations. Our
experiments demonstrate significant performance improvements through hybrid
search methods and structured self-evaluation prompting, achieving up to 72.7%
pass rate on our multi-metric evaluation framework. The results also highlight
the importance of prompt engineering in RAG systems, with our custom-prompted
agents showing consistent improvements in retrieval accuracy and response
quality.
