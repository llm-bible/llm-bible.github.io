---
layout: publication
title: LLMs for Test Input Generation for Semantic Caches
authors: Rasool Zafaryab, Barnett Scott, Willie David, Kurniawan Stefanus, Balugo Sherwin, Thudumu Srikanth, Abdelrazek Mohamed
conference: "Arxiv"
year: 2024
bibkey: rasool2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08138"}
tags: ['Applications', 'LLM', 'Arxiv']
---
Large language models (LLMs) enable state-of-the-art semantic capabilities to be added to software systems such as semantic search of unstructured documents and text generation. However these models are computationally expensive. At scale the cost of serving thousands of users increases massively affecting also user experience. To address this problem semantic caches are used to check for answers to similar queries (that may have been phrased differently) without hitting the LLM service. Due to the nature of these semantic cache techniques that rely on query embeddings there is a high chance of errors impacting user confidence in the system. Adopting semantic cache techniques usually requires testing the effectiveness of a semantic cache (accurate cache hits and misses) which requires a labelled test set of similar queries and responses which is often unavailable. In this paper we present VaryGen an approach for using LLMs for test input generation that produces similar questions from unstructured text documents. Our novel approach uses the reasoning capabilities of LLMs to 1) adapt queries to the domain 2) synthesise subtle variations to queries and 3) evaluate the synthesised test dataset. We evaluated our approach in the domain of a student question and answer system by qualitatively analysing 100 generated queries and result pairs and conducting an empirical case study with an open source semantic cache. Our results show that query pairs satisfy human expectations of similarity and our generated data demonstrates failure cases of a semantic cache. Additionally we also evaluate our approach on Qasper dataset. This work is an important first step into test input generation for semantic applications and presents considerations for practitioners when calibrating a semantic cache.
