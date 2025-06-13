---
layout: publication
title: 'Attackqa: Development And Adoption Of A Dataset For Assisting Cybersecurity Operations Using Fine-tuned And Open-source Llms'
authors: Varun Badrinath Krishna
conference: "Arxiv"
year: 2024
bibkey: krishna2024development
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01073"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Quantization', 'Pretraining Methods', 'Fine-Tuning']
---
Retrieval-augmented generation (RAG) on specialized domain datasets has shown
improved performance when large language models (LLMs) are fine-tuned for
generating responses to user queries. In this study, we develop a cybersecurity
question-answering (Q\&A) dataset, called AttackQA, and employ it to build a
RAG-based Q\&A system designed for analysts in security operations centers. The
dataset comprises 25,335 Q\&A pairs, accompanied by rationales to facilitate
fine-tuning and evaluation. 80% of the dataset was generated with help of a
lightweight open-source LLM (LLama 3 8B), which produced over 1100 tokens per
second with full 16-bit precision on SambaNova System's SN40L specialized
hardware. To ensure dataset quality, we fine-tuned LLama 3 70B to detect and
reject low-quality Q\&A pairs. In using the dataset for RAG, we demonstrate
that fine-tuning open-source embeddings and LLMs can yield superior accuracy
compared to OpenAI's state-of-the-art proprietary embedding and LLM (GPT-4o).
Furthermore, we use Llama 3.1 405B as a judge to evaluate answer correctness,
enabling the creation of a fully open-source, high-speed RAG and evaluation
pipeline with a benchmark for model accuracy.
