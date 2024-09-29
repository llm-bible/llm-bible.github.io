---
layout: publication
title: Boosting Zero45;shot Crosslingual Performance Using Llm45;based Augmentations With Effective Data Selection
authors: Fazili Barah, Agrawal Ashish Sunil, Jyothi Preethi
conference: "Arxiv"
year: 2024
bibkey: fazili2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10582"}
tags: ['Applications', 'Prompting', 'RAG']
---
Large language models (LLMs) are very proficient text generators. We leverage this capability of LLMs to generate task45;specific data via zero45;shot prompting and promote cross45;lingual transfer for low45;resource target languages. Given task45;specific data in a source language and a teacher model trained on this data we propose using this teacher to label LLM generations and employ a set of simple data selection strategies that use the teachers label probabilities. Our data selection strategies help us identify a representative subset of diverse generations that help boost zero45;shot accuracies while being efficient in comparison to using all the LLM generations (without any subset selection). We also highlight other important design choices that affect cross45;lingual performance such as the use of translations of source data and what labels are best to use for the LLM generations. We observe significant performance gains across sentiment analysis and natural language inference tasks (of up to a maximum of 7.13 absolute points and 1.5 absolute points on average) across a number of target languages (Hindi Marathi Urdu Swahili) and domains.
