---
layout: publication
title: Lightweight Large Language Model For Medication Enquiry Med-pal
authors: Elangovan Kabilan, Ong Jasmine Chiat Ling, Jin Liyuan, Seng Benjamin Jun Jie, Kwan Yu Heng, Tan Lit Soo, Zhong Ryan Jian, Ma Justina Koi Li, Ke Yuhe, Liu Nan, Giacomini Kathleen M, Ting Daniel Shu Wei
conference: "Arxiv"
year: 2024
bibkey: elangovan2024lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12822"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Prompting', 'Responsible AI', 'Security']
---
Large Language Models (LLMs) have emerged as a potential solution to assist digital health development with patient education commonly medication-related enquires. We trained and validated Med-Pal a medication domain-specific LLM-chatbot fine-tuned with a fine-grained and expert curated dataset from a selection of five light-weighted open-source LLMs of smaller parameter size (7 billion or less) regarding computational constraints and prioritizing operational efficiency. A multi-disciplinary team performed a clinical evaluation of LLMs responses using the SCORE criteria focusing on safety accuracy bias reproducibility and ease of understanding. Best performing light-weighted LLM was chosen as Med-Pal for further engineering with guard-railing using adversarial prompting. Med-Pal and existing light-weighted LLMs including pretrained Biomistral and finetuned Meerkat were validated on an independent dataset on a broad range of medication-related questions (231 in total) 12 different question types across 14 different medication classes. Mistral-7b emerged as the top performer among selected lightweight LLMs achieving the highest median score of 14 and 71.937; high-quality responses in accuracy and safety domains hence chosen as the backbone LLM for Med-Pal. When compared against Biomistral Med-pal outperformed in generating responses appropriate for patient communication with significant reductions bias and errors typical of general LLMs. Comparable performance was observed when comparing Med-Pal with Meerkat. Med-Pal showcases the feasibility of developing and employing fine-tuned light-weighted LLMs to enhance digital health communications.
