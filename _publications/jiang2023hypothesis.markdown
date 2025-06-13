---
layout: publication
title: 'Hykge: A Hypothesis Knowledge Graph Enhanced Framework For Accurate And Reliable Medical Llms Responses'
authors: Xinke Jiang, Ruizhe Zhang, Yongxin Xu, Rihong Qiu, Yue Fang, Zhiyuan Wang, Jinyi Tang, Hongxin Ding, Xu Chu, Junfeng Zhao, Yasha Wang
conference: "Arxiv"
year: 2023
bibkey: jiang2023hypothesis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15883"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Applications', 'Interpretability and Explainability', 'RAG', 'Interpretability', 'Prompting']
---
In this paper, we investigate the retrieval-augmented generation (RAG) based
on Knowledge Graphs (KGs) to improve the accuracy and reliability of Large
Language Models (LLMs). Recent approaches suffer from insufficient and
repetitive knowledge retrieval, tedious and time-consuming query parsing, and
monotonous knowledge utilization. To this end, we develop a Hypothesis
Knowledge Graph Enhanced (HyKGE) framework, which leverages LLMs' powerful
reasoning capacity to compensate for the incompleteness of user queries,
optimizes the interaction process with LLMs, and provides diverse retrieved
knowledge. Specifically, HyKGE explores the zero-shot capability and the rich
knowledge of LLMs with Hypothesis Outputs to extend feasible exploration
directions in the KGs, as well as the carefully curated prompt to enhance the
density and efficiency of LLMs' responses. Furthermore, we introduce the HO
Fragment Granularity-aware Rerank Module to filter out noise while ensuring the
balance between diversity and relevance in retrieved knowledge. Experiments on
two Chinese medical multiple-choice question datasets and one Chinese
open-domain medical Q&A dataset with two LLM turbos demonstrate the superiority
of HyKGE in terms of accuracy and explainability.
