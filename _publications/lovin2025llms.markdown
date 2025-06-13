---
layout: publication
title: 'Llms To Support A Domain Specific Knowledge Assistant'
authors: Maria-flavia Lovin
conference: "Arxiv"
year: 2025
bibkey: lovin2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04095"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
This work presents a custom approach to developing a domain specific
knowledge assistant for sustainability reporting using the International
Financial Reporting Standards (IFRS). In this domain, there is no publicly
available question-answer dataset, which has impeded the development of a
high-quality chatbot to support companies with IFRS reporting. The two key
contributions of this project therefore are:
  (1) A high-quality synthetic question-answer (QA) dataset based on IFRS
sustainability standards, created using a novel generation and evaluation
pipeline leveraging Large Language Models (LLMs). This comprises 1,063 diverse
QA pairs that address a wide spectrum of potential user queries in
sustainability reporting. Various LLM-based techniques are employed to create
the dataset, including chain-of-thought reasoning and few-shot prompting. A
custom evaluation framework is developed to assess question and answer quality
across multiple dimensions, including faithfulness, relevance, and domain
specificity. The dataset averages a score range of 8.16 out of 10 on these
metrics.
  (2) Two architectures for question-answering in the sustainability reporting
domain - a RAG pipeline and a fully LLM-based pipeline. The architectures are
developed by experimenting, fine-tuning, and training on the QA dataset. The
final pipelines feature an LLM fine-tuned on domain specific data and an
industry classification component to improve the handling of complex queries.
The RAG architecture achieves an accuracy of 85.32% on single-industry and
72.15% on cross-industry multiple-choice questions, outperforming the baseline
approach by 4.67 and 19.21 percentage points, respectively. The LLM-based
pipeline achieves an accuracy of 93.45% on single-industry and 80.30% on
cross-industry multiple-choice questions, an improvement of 12.80 and 27.36
percentage points over the baseline, respectively.
