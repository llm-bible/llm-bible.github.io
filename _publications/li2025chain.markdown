---
layout: publication
title: 'Chain Of Functions: A Programmatic Pipeline For Fine-grained Chart Reasoning Data'
authors: Zijian Li, Jingjing Fu, Lei Song, Jiang Bian, Jun Zhang, Rui Wang
conference: "Arxiv"
year: 2025
bibkey: li2025chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16260"}
tags: ['Multimodal Models', 'RAG', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
Visual reasoning is crucial for multimodal large language models (MLLMs) to
address complex chart queries, yet high-quality rationale data remains scarce.
Existing methods leveraged (M)LLMs for data generation, but direct prompting
often yields limited precision and diversity. In this paper, we propose
\textit\{Chain of Functions (CoF)\}, a novel programmatic reasoning data
generation pipeline that utilizes freely-explored reasoning paths as
supervision to ensure data precision and diversity. Specifically, it starts
with human-free exploration among the atomic functions (e.g., maximum data and
arithmetic operations) to generate diverse function chains, which are then
translated into linguistic rationales and questions with only a moderate
open-sourced LLM. \textit\{CoF\} provides multiple benefits: 1) Precision:
function-governed generation reduces hallucinations compared to freeform
generation; 2) Diversity: enumerating function chains enables varied question
taxonomies; 3) Explainability: function chains serve as built-in rationales,
allowing fine-grained evaluation beyond overall accuracy; 4) Practicality:
eliminating reliance on extremely large models. Employing \textit\{CoF\}, we
construct the \textit\{ChartCoF\} dataset, with 1.4k complex reasoning Q\&A for
fine-grained analysis and 50k Q\&A for reasoning enhancement. The fine-grained
evaluation on \textit\{ChartCoF\} reveals varying performance across question
taxonomies for each MLLM, and the experiments also show that finetuning with
\textit\{ChartCoF\} achieves state-of-the-art performance among same-scale MLLMs
on widely used benchmarks. Furthermore, the novel paradigm of function-governed
rationale generation in \textit\{CoF\} could inspire broader applications beyond
charts.
