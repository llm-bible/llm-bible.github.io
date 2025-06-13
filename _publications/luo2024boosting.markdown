---
layout: publication
title: 'Personamath: Boosting Mathematical Reasoning Via Persona-driven Data Augmentation'
authors: Jing Luo, Longze Chen, Run Luo, Liang Zhu, Chang Ao, Jiaming Li, Yukun Chen, Xin Cheng, Wen Yang, Jiayuan Su, Ahmadreza Argha, Hamid Alinejad-rokny, Chengming Li, Shiwen Ni, Min Yang
conference: "Arxiv"
year: 2024
bibkey: luo2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01504"}
tags: ['RAG', 'Training Techniques']
---
While closed-source Large Language Models (LLMs) demonstrate strong
mathematical problem-solving abilities, open-source models still face
challenges with such tasks. To bridge this gap, we propose a data augmentation
approach and introduce PersonaMathQA, a dataset derived from MATH and GSM8K, on
which we train the PersonaMath models. Our approach consists of two stages: the
first stage focuses on learning from Persona Diversification, and the second
stage emphasizes learning from Reflection. In the first stage, we regenerate
detailed chain-of-thought (CoT) solutions as instructions using a closed-source
LLM and introduce a persona-driven data augmentation technique. This technique
innovatively classifies personas based on occupations, significantly enhancing
the dataset's diversity and quality. In the second stage, we incorporate
reflection to fully leverage more challenging and valuable questions.
Evaluation of our PersonaMath models on MATH and GSM8K reveals that the
PersonaMath-7B model (based on Qwen2.5-7B) achieves an accuracy of 61.2% on
MATH and 87.8% on GSM8K, surpassing all baseline methods and achieving
state-of-the-art performance. Notably, our dataset contains only 128.9K data
points-merely 32.6% of MetaMathQA and 49.5% of MathInstruct-yet our model
outperforms these baselines, demonstrating the high quality and diversity of
our dataset, which enables more efficient model training. We open-source the
PersonaMathQA dataset, PersonaMath models, and our code for public usage.
