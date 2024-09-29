---
layout: publication
title: Beyond English Evaluating LLMs for Arabic Grammatical Error Correction
authors: Kwon Sang Yun, Bhatia Gagan, Nagoudi El Moatez Billah, Abdul-mageed Muhammad
conference: "Arxiv"
year: 2023
bibkey: kwon2023beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.08400"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) finetuned to follow human instruction have recently exhibited significant capabilities in various English NLP tasks. However their performance in grammatical error correction (GEC) especially on languages other than English remains significantly unexplored. In this work we evaluate the abilities of instruction finetuned LLMs in Arabic GEC a complex task due to Arabics rich morphology. Our findings suggest that various prompting methods coupled with (in-context) few-shot learning demonstrate considerable effectiveness with GPT-4 achieving up to 65.49 F_1 score under expert prompting (approximately 5 points higher than our established baseline). Despite these positive results we find that instruction finetuned models regardless of their size are still outperformed by fully finetuned ones even if they are significantly smaller in size. This disparity highlights substantial room for improvements for LLMs. Inspired by methods used in low-resource machine translation we also develop a method exploiting synthetic data that significantly outperforms previous models on two standard Arabic benchmarks. Our best model achieves a new SOTA on Arabic GEC with 73.29 and 73.26 F_1 on the 2014 and 2015 QALB datasets respectively compared to peer-reviewed published baselines.
