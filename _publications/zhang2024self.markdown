---
layout: publication
title: Self-Tuning Instructing LLMs to Effectively Acquire New Knowledge through Self-Teaching
authors: Zhang Xiaoying, Peng Baolin, Tian Ye, Zhou Jingyan, Zhang Yipeng, Mi Haitao, Meng Helen
conference: "Arxiv"
year: 2024
bibkey: zhang2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06326"}
tags: ['Supervised', 'Self-Supervised', 'Pretraining Methods', 'Arxiv']
---
Large language models (LLMs) often struggle to provide up-to-date information due to their one-time training and the constantly evolving nature of the world. To keep LLMs current existing approaches typically involve continued pre-training on new documents. However they frequently face difficulties in extracting stored knowledge. Motivated by the remarkable success of the Feynman Technique in efficient human learning we introduce Self-Tuning a learning framework aimed at improving an LLMs ability to effectively acquire new knowledge from raw documents through self-teaching. Specifically we develop a Self-Teaching strategy that augments the documents with a set of knowledge-intensive tasks created in a self-supervised manner focusing on three crucial aspects memorization comprehension and self-reflection. In addition we introduce three Wiki-Newpages-2023-QA datasets to facilitate an in-depth analysis of an LLMs knowledge acquisition ability concerning memorization extraction and reasoning. Extensive experimental results on Llama2 family models reveal that Self-Tuning consistently exhibits superior performance across all knowledge acquisition tasks and excels in preserving previous knowledge.
