---
layout: publication
title: 'Translate With Care: Addressing Gender Bias, Neutrality, And Reasoning In Large Language Model Translations'
authors: Pardis Sadat Zahraei, Ali Emami
conference: "Arxiv"
year: 2025
bibkey: zahraei2025translate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00748"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Addressing gender bias and maintaining logical coherence in machine translation remains challenging, particularly when translating between natural gender languages, like English, and genderless languages, such as Persian, Indonesian, and Finnish. We introduce the Translate-with-Care (TWC) dataset, comprising 3,950 challenging scenarios across six low- to mid-resource languages, to assess translation systems' performance. Our analysis of diverse technologies, including GPT-4, mBART-50, NLLB-200, and Google Translate, reveals a universal struggle in translating genderless content, resulting in gender stereotyping and reasoning errors. All models preferred masculine pronouns when gender stereotypes could influence choices. Google Translate and GPT-4 showed particularly strong bias, favoring male pronouns 4-6 times more than feminine ones in leadership and professional success contexts. Fine-tuning mBART-50 on TWC substantially resolved these biases and errors, led to strong generalization, and surpassed proprietary LLMs while remaining open-source. This work emphasizes the need for targeted approaches to gender and semantic coherence in machine translation, particularly for genderless languages, contributing to more equitable and accurate translation systems.
