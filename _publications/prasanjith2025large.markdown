---
layout: publication
title: 'Indicragsuite: Large-scale Datasets And A Benchmark For Indian Language RAG Systems'
authors: Pasunuti Prasanjith, Prathmesh B More, Anoop Kunchukuttan, Raj Dabre
conference: "Arxiv"
year: 2025
bibkey: prasanjith2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01615'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques', 'Large-Scale Training']
---
Retrieval-Augmented Generation (RAG) systems enable language models to access relevant information and generate accurate, well-grounded, and contextually informed responses. However, for Indian languages, the development of high-quality RAG systems is hindered by the lack of two critical resources: (1) evaluation benchmarks for retrieval and generation tasks, and (2) large-scale training datasets for multilingual retrieval. Most existing benchmarks and datasets are centered around English or high-resource languages, making it difficult to extend RAG capabilities to the diverse linguistic landscape of India. To address the lack of evaluation benchmarks, we create IndicMSMarco, a multilingual benchmark for evaluating retrieval quality and response generation in 13 Indian languages, created via manual translation of 1000 diverse queries from MS MARCO-dev set. To address the need for training data, we build a large-scale dataset of (question, answer, relevant passage) tuples derived from the Wikipedias of 19 Indian languages using state-of-the-art LLMs. Additionally, we include translated versions of the original MS MARCO dataset to further enrich the training data and ensure alignment with real-world information-seeking tasks. Resources are available here: https://huggingface.co/collections/ai4bharat/indicragsuite-683e7273cb2337208c8c0fcb
