---
layout: publication
title: MELA Multilingual Evaluation Of Linguistic Acceptability
authors: Zhang Ziyin, Liu Yikang, Huang Weifang, Mao Junyu, Wang Rui, Hu Hai
conference: "Arxiv"
year: 2023
bibkey: zhang2023mela
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09033"}
  - {name: "Code", url: "https://github.com/sjtu-compling/MELA"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
In this work we present the largest benchmark to date on linguistic acceptability Multilingual Evaluation of Linguistic Acceptability -- MELA with 46K samples covering 10 languages from a diverse set of language families. We establish LLM baselines on this benchmark and investigate cross-lingual transfer in acceptability judgements with XLM-R. In pursuit of multilingual interpretability we conduct probing experiments with fine-tuned XLM-R to explore the process of syntax capability acquisition. Our results show that GPT-4o exhibits a strong multilingual ability outperforming fine-tuned XLM-R while open-source multilingual models lag behind by a noticeable gap. Cross-lingual transfer experiments show that transfer in acceptability judgment is non-trivial 500 Icelandic fine-tuning examples lead to 23 MCC performance in a completely unrelated language -- Chinese. Results of our probing experiments indicate that training on MELA improves the performance of XLM-R on syntax-related tasks. Our data is available at https://github.com/sjtu-compling/MELA.
