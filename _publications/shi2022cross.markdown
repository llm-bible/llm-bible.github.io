---
layout: publication
title: XRICL Cross45;lingual Retrieval45;augmented In45;context Learning For Cross45;lingual Text45;to45;sql Semantic Parsing
authors: Shi Peng, Zhang Rui, Bai He, Lin Jimmy
conference: "Arxiv"
year: 2022
bibkey: shi2022cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.13693"}
  - {name: "Code", url: "https://github.com/Impavidity/XRICL"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
In45;context learning using large language models has recently shown surprising results for semantic parsing tasks such as Text45;to45;SQL translation. Prompting GPT45;3 or Codex using several examples of question45;SQL pairs can produce excellent results comparable to state45;of45;the45;art finetuning45;based models. However existing work primarily focuses on English datasets and it is unknown whether large language models can serve as competitive semantic parsers for other languages. To bridge this gap our work focuses on cross45;lingual Text45;to45;SQL semantic parsing for translating non45;English utterances into SQL queries based on an English schema. We consider a zero45;shot transfer learning setting with the assumption that we do not have any labeled examples in the target language (but have annotated examples in English). This work introduces the XRICL framework which learns to retrieve relevant English exemplars for a given query to construct prompts. We also include global translation exemplars for a target language to facilitate the translation process for large language models. To systematically evaluate our model we construct two new benchmark datasets XSpider and XKaggle45;dbqa which include questions in Chinese Vietnamese Farsi and Hindi. Our experiments show that XRICL effectively leverages large pre45;trained language models to outperform existing baselines. Data and code are publicly available at https://github.com/Impavidity/XRICL.
