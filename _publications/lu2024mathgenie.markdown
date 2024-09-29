---
layout: publication
title: Mathgenie Generating Synthetic Data With Question Back-translation For Enhancing Mathematical Reasoning Of Llms
authors: Lu Zimu, Zhou Aojun, Ren Houxing, Wang Ke, Shi Weikang, Pan Junting, Zhan Mingjie, Li Hongsheng
conference: "Arxiv"
year: 2024
bibkey: lu2024mathgenie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16352"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods']
---
Large language models (LLMs) have exhibited great potential in mathematical reasoning. However there remains a performance gap in this area between existing open-source models and closed-source models such as GPT-4. In this paper we introduce MathGenie a novel method for generating diverse and reliable math problems from a small-scale problem-solution dataset (denoted as seed data). We augment the ground-truth solutions of our seed data and train a back-translation model to translate the augmented solutions back into new questions. Subsequently we generate code-integrated solutions for the new questions. To ensure the correctness of the code-integrated solutions we employ rationale-based strategy for solution verification. Various pretrained models ranging from 7B to 70B are trained on the newly curated data to test the effectiveness of the proposed augmentation technique resulting in a family of models known as MathGenieLM. These models consistently outperform previous open-source models across five representative mathematical reasoning datasets achieving state-of-the-art performance. In particular MathGenieLM-InternLM2 achieves an accuracy of 87.737; on GSM8K and 55.737; on MATH securing the best overall score among open-source language models.
