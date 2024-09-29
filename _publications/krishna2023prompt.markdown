---
layout: publication
title: Prompt Generate Train (PGT)\: Few-shot Domain Adaption Of Retrieval Augmented Generation Models For Open Book Question-answering
authors: Krishna C. S.
conference: "Arxiv"
year: 2023
bibkey: krishna2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.05915"}
tags: ['Agentic', 'BERT', 'Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We propose a framework - Prompt Generate Train (PGT) - to efficiently develop a generative question-answering model for open-book question-answering over a proprietary collection of text documents. The framework adapts a retriever augmented generation (RAG) model to the target domain using supervised fine-tuning and reinforcement learning with synthetic feedback in a few-shot setting. This we hypothesize will yield an aligned uncertainty calibrated model that is competitive with GPT-4 based in-context retrieval augmented generation in generating relevant answers at lower serving costs. The frameworks synthetic generation pipeline will generate synthetic training data comprising <passage question answer tuples using an open-source LLM and a novel consistency filtering scheme. The pipeline will be designed to generate both abstractive and extractive questions that span the entire corpus. The framework proposes to fine-tune a smaller RAG model comprising a dense retriever (ColBERTv2) and a smaller sized LLM on the synthetic dataset. In parallel the framework will train a Reward model to score domain grounded answers higher than hallucinated answers using an a priori relevance ordering of synthetically assembled samples. In the next phase the framework will align the RAG model with the target domain using reinforcement learning (Proximal Policy Optimization). This step may improve the RAG models ability to generate grounded answers and ignore out of domain questions. In the final phase the framework will calibrate the models uncertainty for extractive question-answers.
