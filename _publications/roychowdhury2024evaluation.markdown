---
layout: publication
title: 'Evaluation Of RAG Metrics For Question Answering In The Telecom Domain'
authors: Sujoy Roychowdhury, Sumit Soman, H G Ranjani, Neeraj Gunda, Vansh Chhabra, Sai Krishna Bala
conference: "Arxiv"
year: 2024
bibkey: roychowdhury2024evaluation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.12873'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'Pretraining Methods']
---
Retrieval Augmented Generation (RAG) is widely used to enable Large Language
Models (LLMs) perform Question Answering (QA) tasks in various domains.
However, RAG based on open-source LLM for specialized domains has challenges of
evaluating generated responses. A popular framework in the literature is the
RAG Assessment (RAGAS), a publicly available library which uses LLMs for
evaluation. One disadvantage of RAGAS is the lack of details of derivation of
numerical value of the evaluation metrics. One of the outcomes of this work is
a modified version of this package for few metrics (faithfulness, context
relevance, answer relevance, answer correctness, answer similarity and factual
correctness) through which we provide the intermediate outputs of the prompts
by using any LLMs. Next, we analyse the expert evaluations of the output of the
modified RAGAS package and observe the challenges of using it in the telecom
domain. We also study the effect of the metrics under correct vs. wrong
retrieval and observe that few of the metrics have higher values for correct
retrieval. We also study for differences in metrics between base embeddings and
those domain adapted via pre-training and fine-tuning. Finally, we comment on
the suitability and challenges of using these metrics for in-the-wild telecom
QA task.
