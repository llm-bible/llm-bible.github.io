---
layout: publication
title: Relation Extraction With Fine45;tuned Large Language Models In Retrieval Augmented Generation Frameworks
authors: Efeoglu Sefika, Paschke Adrian
conference: "Arxiv"
year: 2024
bibkey: efeoglu2024relation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14745"}
tags: ['Applications', 'Fine Tuning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Information Extraction (IE) is crucial for converting unstructured data into structured formats like Knowledge Graphs (KGs). A key task within IE is Relation Extraction (RE) which identifies relationships between entities in text. Various RE methods exist including supervised unsupervised weakly supervised and rule45;based approaches. Recent studies leveraging pre45;trained language models (PLMs) have shown significant success in this area. In the current era dominated by Large Language Models (LLMs) fine45;tuning these models can overcome limitations associated with zero45;shot LLM prompting45;based RE methods especially regarding domain adaptation challenges and identifying implicit relations between entities in sentences. These implicit relations which cannot be easily extracted from a sentences dependency tree require logical inference for accurate identification. This work explores the performance of fine45;tuned LLMs and their integration into the Retrieval Augmented45;based (RAG) RE approach to address the challenges of identifying implicit relations at the sentence level particularly when LLMs act as generators within the RAG framework. Empirical evaluations on the TACRED TACRED45;Revisited (TACREV) Re45;TACRED and SemEVAL datasets show significant performance improvements with fine45;tuned LLMs including Llama245;7B Mistral45;7B and T5 (Large). Notably our approach achieves substantial gains on SemEVAL where implicit relations are common surpassing previous results on this dataset. Additionally our method outperforms previous works on TACRED TACREV and Re45;TACRED demonstrating exceptional performance across diverse evaluation scenarios.
