---
layout: publication
title: 'Does Prompt Design Impact Quality Of Data Imputation By Llms?'
authors: Shreenidhi Srinivasan, Lydia Manikonda
conference: "Arxiv"
year: 2025
bibkey: srinivasan2025does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04172"}
tags: ['RAG', 'Prompting', 'In-Context Learning']
---
Generating realistic synthetic tabular data presents a critical challenge in machine learning. It adds another layer of complexity when this data contain class imbalance problems. This paper presents a novel token-aware data imputation method that leverages the in-context learning capabilities of large language models. This is achieved through the combination of a structured group-wise CSV-style prompting technique and the elimination of irrelevant contextual information in the input prompt. We test this approach with two class-imbalanced binary classification datasets and evaluate the effectiveness of imputation using classification-based evaluation metrics. The experimental results demonstrate that our approach significantly reduces the input prompt size while maintaining or improving imputation quality compared to our baseline prompt, especially for datasets that are of relatively smaller in size. The contributions of this presented work is two-fold -- 1) it sheds light on the importance of prompt design when leveraging LLMs for synthetic data generation and 2) it addresses a critical gap in LLM-based data imputation for class-imbalanced datasets with missing data by providing a practical solution within computational constraints. We hope that our work will foster further research and discussions about leveraging the incredible potential of LLMs and prompt engineering techniques for synthetic data generation.
