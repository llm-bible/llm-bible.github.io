---
layout: publication
title: 'Large Language Models Can Automatically Engineer Features For Few-shot Tabular Learning'
authors: Sungwon Han, Jinsung Yoon, Sercan O Arik, Tomas Pfister
conference: "Arxiv"
year: 2024
bibkey: han2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09491"}
tags: ['Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications', 'In-Context Learning']
---
Large Language Models (LLMs), with their remarkable ability to tackle
challenging and unseen reasoning problems, hold immense potential for tabular
learning, that is vital for many real-world applications. In this paper, we
propose a novel in-context learning framework, FeatLLM, which employs LLMs as
feature engineers to produce an input data set that is optimally suited for
tabular predictions. The generated features are used to infer class likelihood
with a simple downstream machine learning model, such as linear regression and
yields high performance few-shot learning. The proposed FeatLLM framework only
uses this simple predictive model with the discovered features at inference
time. Compared to existing LLM-based approaches, FeatLLM eliminates the need to
send queries to the LLM for each sample at inference time. Moreover, it merely
requires API-level access to LLMs, and overcomes prompt size limitations. As
demonstrated across numerous tabular datasets from a wide range of domains,
FeatLLM generates high-quality rules, significantly (10% on average)
outperforming alternatives such as TabLLM and STUNT.
