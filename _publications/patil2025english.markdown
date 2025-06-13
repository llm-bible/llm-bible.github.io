---
layout: publication
title: 'English Please: Evaluating Machine Translation With Large Language Models For Multilingual Bug Reports'
authors: Avinash Patil, Siru Tao, Aryan Jadon
conference: "Arxiv"
year: 2025
bibkey: patil2025english
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14338"}
  - {name: "Code", url: "https://github.com/av9ash/English-Please"}
tags: ['Model Architecture', 'GPT', 'BERT', 'Fine-Tuning', 'Has Code', 'Applications']
---
Accurate translation of bug reports is critical for efficient collaboration in global software development. In this study, we conduct the first comprehensive evaluation of machine translation (MT) performance on bug reports, analyzing the capabilities of DeepL, AWS Translate, and large language models such as ChatGPT, Claude, Gemini, LLaMA, and Mistral using data from the Visual Studio Code GitHub repository, specifically focusing on reports labeled with the english-please tag. To assess both translation quality and source language identification accuracy, we employ a range of MT evaluation metrics-including BLEU, BERTScore, COMET, METEOR, and ROUGE-alongside classification metrics such as accuracy, precision, recall, and F1-score. Our findings reveal that while ChatGPT (gpt-4o) excels in semantic and lexical translation quality, it does not lead in source language identification. Claude and Mistral achieve the highest F1-scores (0.7182 and 0.7142, respectively), and Gemini records the best precision (0.7414). AWS Translate shows the highest accuracy (0.4717) in identifying source languages. These results highlight that no single system dominates across all tasks, reinforcing the importance of task-specific evaluations. This study underscores the need for domain adaptation when translating technical content and provides actionable insights for integrating MT into bug-triaging workflows. The code and dataset for this paper are available at GitHub-https://github.com/av9ash/English-Please
