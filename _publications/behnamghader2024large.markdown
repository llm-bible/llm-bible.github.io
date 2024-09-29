---
layout: publication
title: "Llm2vec: Large Language Models Are Secretly Powerful Text Encoders"
authors: Behnamghader Parishad, Adlakha Vaibhav, Mosbach Marius, Bahdanau Dzmitry, Chapados Nicolas, Reddy Siva
conference: "Arxiv"
year: 2024
bibkey: behnamghader2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05961"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods']
---
Large decoder-only language models (LLMs) are the state-of-the-art models on most of todays NLP tasks and benchmarks. Yet the community is only slowly adopting these models for text embedding tasks which require rich contextualized representations. In this work we introduce LLM2Vec a simple unsupervised approach that can transform any decoder-only LLM into a strong text encoder. LLM2Vec consists of three simple steps 1) enabling bidirectional attention 2) masked next token prediction and 3) unsupervised contrastive learning. We demonstrate the effectiveness of LLM2Vec by applying it to 4 popular LLMs ranging from 1.3B to 8B parameters and evaluate the transformed models on English word- and sequence-level tasks. We outperform encoder-only models by a large margin on word-level tasks and reach a new unsupervised state-of-the-art performance on the Massive Text Embeddings Benchmark (MTEB). Moreover when combining LLM2Vec with supervised contrastive learning we achieve state-of-the-art performance on MTEB among models that train only on publicly available data (as of May 24 2024). Our strong empirical results and extensive analysis demonstrate that LLMs can be effectively transformed into universal text encoders in a parameter-efficient manner without the need for expensive adaptation or synthetic GPT-4 generated data.
