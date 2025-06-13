---
layout: publication
title: 'Cs-sum: A Benchmark For Code-switching Dialogue Summarization And The Limits Of Large Language Models'
authors: Sathya Krishnan Suresh, Tanmay Surana, Lim Zhi Hao, Eng Siong Chng
conference: "Arxiv"
year: 2025
bibkey: suresh2025cs
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13559"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Pretraining Methods', 'Few-Shot']
---
Code-switching (CS) poses a significant challenge for Large Language Models (LLMs), yet its comprehensibility remains underexplored in LLMs. We introduce CS-Sum, to evaluate the comprehensibility of CS by the LLMs through CS dialogue to English summarization. CS-Sum is the first benchmark for CS dialogue summarization across Mandarin-English (EN-ZH), Tamil-English (EN-TA), and Malay-English (EN-MS), with 900-1300 human-annotated dialogues per language pair. Evaluating ten LLMs, including open and closed-source models, we analyze performance across few-shot, translate-summarize, and fine-tuning (LoRA, QLoRA on synthetic data) approaches. Our findings show that though the scores on automated metrics are high, LLMs make subtle mistakes that alter the complete meaning of the dialogue. To this end, we introduce 3 most common type of errors that LLMs make when handling CS input. Error rates vary across CS pairs and LLMs, with some LLMs showing more frequent errors on certain language pairs, underscoring the need for specialized training on code-switched data.
