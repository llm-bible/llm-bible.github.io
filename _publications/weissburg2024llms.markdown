---
layout: publication
title: 'Llms Are Biased Teachers: Evaluating LLM Bias In Personalized Education'
authors: Iain Weissburg, Sathvika Anand, Sharon Levy, Haewon Jeong
conference: "Arxiv"
year: 2024
bibkey: weissburg2024llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14012'}
tags: ['Ethics and Bias', 'Interpretability and Explainability']
---
With the increasing adoption of large language models (LLMs) in education,
concerns about inherent biases in these models have gained prominence. We
evaluate LLMs for bias in the personalized educational setting, specifically
focusing on the models' roles as "teachers." We reveal significant biases in
how models generate and select educational content tailored to different
demographic groups, including race, ethnicity, sex, gender, disability status,
income, and national origin. We introduce and apply two bias score
metrics--Mean Absolute Bias (MAB) and Maximum Difference Bias (MDB)--to analyze
9 open and closed state-of-the-art LLMs. Our experiments, which utilize over
17,000 educational explanations across multiple difficulty levels and topics,
uncover that models potentially harm student learning by both perpetuating
harmful stereotypes and reversing them. We find that bias is similar for all
frontier models, with the highest MAB along income levels while MDB is highest
relative to both income and disability status. For both metrics, we find the
lowest bias exists for sex/gender and race/ethnicity.
