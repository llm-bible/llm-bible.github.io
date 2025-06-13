---
layout: publication
title: 'Enhancing Q&A With Domain-specific Fine-tuning And Iterative Reasoning: A Comparative Study'
authors: Zooey Nguyen, Anthony Annunziata, Vinh Luong, Sang Dinh, Quynh Le, Anh Hai Ha, Chanh Le, Hong An Phan, Shruti Raghavan, Christopher Nguyen
conference: "Arxiv"
year: 2024
bibkey: nguyen2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11792"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
This paper investigates the impact of domain-specific model fine-tuning and
of reasoning mechanisms on the performance of question-answering (Q&A) systems
powered by large language models (LLMs) and Retrieval-Augmented Generation
(RAG). Using the FinanceBench SEC financial filings dataset, we observe that,
for RAG, combining a fine-tuned embedding model with a fine-tuned LLM achieves
better accuracy than generic models, with relatively greater gains attributable
to fine-tuned embedding models. Additionally, employing reasoning iterations on
top of RAG delivers an even bigger jump in performance, enabling the Q&A
systems to get closer to human-expert quality. We discuss the implications of
such findings, propose a structured technical design space capturing major
technical components of Q&A AI, and provide recommendations for making
high-impact technical choices for such components. We plan to follow up on this
work with actionable guides for AI teams and further investigations into the
impact of domain-specific augmentation in RAG and into agentic AI capabilities
such as advanced planning and reasoning.
