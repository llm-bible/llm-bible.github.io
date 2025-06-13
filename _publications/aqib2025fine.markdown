---
layout: publication
title: 'Fine-tuning Large Language Models And Evaluating Retrieval Methods For Improved Question Answering On Building Codes'
authors: Mohammad Aqib, Mohd Hamza, Qipei Mei, Ying Hei Chui
conference: "Arxiv"
year: 2025
bibkey: aqib2025fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.04666'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
Building codes are regulations that establish standards for the design,
construction, and safety of buildings to ensure structural integrity, fire
protection, and accessibility. They are often extensive, complex, and subject
to frequent updates, making manual querying challenging and time-consuming. Key
difficulties include navigating large volumes of text, interpreting technical
language, and identifying relevant clauses across different sections. A
potential solution is to build a Question-Answering (QA) system that answers
user queries based on building codes. Among the various methods for building a
QA system, Retrieval-Augmented Generation (RAG) stands out in performance. RAG
consists of two components: a retriever and a language model. This study
focuses on identifying a suitable retriever method for building codes and
optimizing the generational capability of the language model using fine-tuning
techniques. We conducted a detailed evaluation of various retrieval methods by
performing the retrieval on the National Building Code of Canada (NBCC) and
explored the impact of domain-specific fine-tuning on several language models
using the dataset derived from NBCC. Our analysis included a comparative
assessment of different retrievers and the performance of both pre-trained and
fine-tuned models to determine the efficacy and domain-specific adaptation of
language models using fine-tuning on the NBCC dataset. Experimental results
showed that Elasticsearch proved to be the most robust retriever among all. The
findings also indicate that fine-tuning language models on an NBCC-specific
dataset can enhance their ability to generate contextually relevant responses.
When combined with context retrieved by a powerful retriever like
Elasticsearch, this improvement in LLM performance can optimize the RAG system,
enabling it to better navigate the complexities of the NBCC.
