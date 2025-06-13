---
layout: publication
title: 'Domain-specific Retrieval-augmented Generation Using Vector Stores, Knowledge Graphs, And Tensor Factorization'
authors: Ryan C. Barron, Ves Grantcharov, Selma Wanna, Maksim E. Eren, Manish Bhattarai, Nicholas Solovyev, George Tompkins, Charles Nicholas, Kim Ø. Rasmussen, Cynthia Matuszek, Boian S. Alexandrov
conference: "Arxiv"
year: 2024
bibkey: barron2024domain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02721'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Prompting', 'KDD', 'Pretraining Methods']
---
Large Language Models (LLMs) are pre-trained on large-scale corpora and excel
in numerous general natural language processing (NLP) tasks, such as question
answering (QA). Despite their advanced language capabilities, when it comes to
domain-specific and knowledge-intensive tasks, LLMs suffer from hallucinations,
knowledge cut-offs, and lack of knowledge attributions. Additionally, fine
tuning LLMs' intrinsic knowledge to highly specific domains is an expensive and
time consuming process. The retrieval-augmented generation (RAG) process has
recently emerged as a method capable of optimization of LLM responses, by
referencing them to a predetermined ontology. It was shown that using a
Knowledge Graph (KG) ontology for RAG improves the QA accuracy, by taking into
account relevant sub-graphs that preserve the information in a structured
manner. In this paper, we introduce SMART-SLIC, a highly domain-specific LLM
framework, that integrates RAG with KG and a vector store (VS) that store
factual domain specific information. Importantly, to avoid hallucinations in
the KG, we build these highly domain-specific KGs and VSs without the use of
LLMs, but via NLP, data mining, and nonnegative tensor factorization with
automatic model selection. Pairing our RAG with a domain-specific: (i) KG
(containing structured information), and (ii) VS (containing unstructured
information) enables the development of domain-specific chat-bots that
attribute the source of information, mitigate hallucinations, lessen the need
for fine-tuning, and excel in highly domain-specific question answering tasks.
We pair SMART-SLIC with chain-of-thought prompting agents. The framework is
designed to be generalizable to adapt to any specific or specialized domain. In
this paper, we demonstrate the question answering capabilities of our framework
on a corpus of scientific publications on malware analysis and anomaly
detection.
