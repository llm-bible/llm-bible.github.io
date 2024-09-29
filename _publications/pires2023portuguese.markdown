---
layout: publication
title: Sabia Portuguese Large Language Models
authors: Pires Ramon, Abonizio Hugo, Almeida Thales Sales, Nogueira Rodrigo
conference: "Arxiv"
year: 2023
bibkey: pires2023portuguese
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07880"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
As the capabilities of language models continue to advance it is conceivable that one45;size45;fits45;all model will remain as the main paradigm. For instance given the vast number of languages worldwide many of which are low45;resource the prevalent practice is to pretrain a single model on multiple languages. In this paper we add to the growing body of evidence that challenges this practice demonstrating that monolingual pretraining on the target language significantly improves models already extensively trained on diverse corpora. More specifically we further pretrain GPT45;J and LLaMA models on Portuguese texts using 337; or less of their original pretraining budget. Few45;shot evaluations on Poeta a suite of 14 Portuguese datasets reveal that our models outperform English45;centric and multilingual counterparts by a significant margin. Our best model Sabia45;65B performs on par with GPT45;3.545;turbo. By evaluating on datasets originally conceived in the target language as well as translated ones we study the contributions of language45;specific pretraining in terms of 1) capturing linguistic nuances and structures inherent to the target language and 2) enriching the models knowledge about a domain or culture. Our results indicate that the majority of the benefits stem from the domain45;specific knowledge acquired through monolingual pretraining.
