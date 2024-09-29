---
layout: publication
title: Leveraging Llms For Synthesizing Training Data Across Many Languages In Multilingual Dense Retrieval
authors: Thakur Nandan, Ni Jianmo, Ábrego Gustavo Hernández, Wieting John, Lin Jimmy, Cer Daniel
conference: "Arxiv"
year: 2023
bibkey: thakur2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05800"}
  - {name: "Code", url: "https://github.com/google&#45;research&#45;datasets/SWIM&#45;IR"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
There has been limited success for dense retrieval models in multilingual retrieval due to uneven and scarce training data available across multiple languages. Synthetic training data generation is promising (e.g. InPars or Promptagator) but has been investigated only for English. Therefore to study model capabilities across both cross45;lingual and monolingual retrieval tasks we develop SWIM45;IR a synthetic retrieval training dataset containing 33 (high to very45;low resource) languages for fine45;tuning multilingual dense retrievers without requiring any human supervision. To construct SWIM45;IR we propose SAP (summarize45;then45;ask prompting) where the large language model (LLM) generates a textual summary prior to the query generation step. SAP assists the LLM in generating informative queries in the target language. Using SWIM45;IR we explore synthetic fine45;tuning of multilingual dense retrieval models and evaluate them robustly on three retrieval benchmarks XOR45;Retrieve (cross45;lingual) MIRACL (monolingual) and XTREME45;UP (cross45;lingual). Our models called SWIM45;X are competitive with human45;supervised dense retrieval models e.g. mContriever45;X finding that SWIM45;IR can cheaply substitute for expensive human45;labeled retrieval training data. SWIM45;IR dataset and SWIM45;X models are available at https://github.com/google&#45;research&#45;datasets/SWIM&#45;IR.
