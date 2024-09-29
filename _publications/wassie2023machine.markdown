---
layout: publication
title: Machine Translation For Geez Language
authors: Wassie Aman Kassahun
conference: "Arxiv"
year: 2023
bibkey: wassie2023machine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.14530"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Machine translation (MT) for low-resource languages such as Geez an ancient language that is no longer the native language of any community faces challenges such as out-of-vocabulary words domain mismatches and lack of sufficient labeled training data. In this work we explore various methods to improve Geez MT including transfer-learning from related languages optimizing shared vocabulary and token segmentation approaches finetuning large pre-trained models and using large language models (LLMs) for few-shot translation with fuzzy matches. We develop a multilingual neural machine translation (MNMT) model based on languages relatedness which brings an average performance improvement of about 4 BLEU compared to standard bilingual models. We also attempt to finetune the NLLB-200 model one of the most advanced translation models available today but find that it performs poorly with only 4k training samples for Geez. Furthermore we experiment with using GPT-3.5 a state-of-the-art LLM for few-shot translation with fuzzy matches which leverages embedding similarity-based retrieval to find context examples from a parallel corpus. We observe that GPT-3.5 achieves a remarkable BLEU score of 9.2 with no initial knowledge of Geez but still lower than the MNMT baseline of 15.2. Our work provides insights into the potential and limitations of different approaches for low-resource and ancient language MT.
