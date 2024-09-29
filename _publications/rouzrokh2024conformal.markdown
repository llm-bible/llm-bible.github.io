---
layout: publication
title: CONFLARE\: Conformal Large Language Model Retrieval
authors: Rouzrokh Pouria, Faghani Shahriar, Gamble Cooper U., Shariatnia Moein, Erickson Bradley J.
conference: "Arxiv"
year: 2024
bibkey: rouzrokh2024conformal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04287"}
tags: ['RAG', 'Tools', 'Training Techniques']
---
Retrieval-augmented generation (RAG) frameworks enable large language models (LLMs) to retrieve relevant information from a knowledge base and incorporate it into the context for generating responses. This mitigates hallucinations and allows for the updating of knowledge without retraining the LLM. However RAG does not guarantee valid responses if retrieval fails to identify the necessary information as the context for response generation. Also if there is contradictory content the RAG response will likely reflect only one of the two possible responses. Therefore quantifying uncertainty in the retrieval process is crucial for ensuring RAG trustworthiness. In this report we introduce a four-step framework for applying conformal prediction to quantify retrieval uncertainty in RAG frameworks. First a calibration set of questions answerable from the knowledge base is constructed. Each questions embedding is compared against document embeddings to identify the most relevant document chunks containing the answer and record their similarity scores. Given a user-specified error rate ((alpha)) these similarity scores are then analyzed to determine a similarity score cutoff threshold. During inference all chunks with similarity exceeding this threshold are retrieved to provide context to the LLM ensuring the true answer is captured in the context with a (1-(alpha)) confidence level. We provide a Python package that enables users to implement the entire workflow proposed in our work only using LLMs and without human intervention.
