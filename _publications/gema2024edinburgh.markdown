---
layout: publication
title: Edinburgh Clinical NLP at SemEval-2024 Task 2 Fine-tune your model unless you have access to GPT-4
authors: Gema Aryo Pradipta, Hong Giwon, Minervini Pasquale, Daines Luke, Alex Beatrice
conference: "Arxiv"
year: 2024
bibkey: gema2024edinburgh
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00484"}
tags: ['ARXIV', 'GPT', 'Language Modeling', 'Pretraining Methods']
---
The NLI4CT task assesses Natural Language Inference systems in predicting whether hypotheses entail or contradict evidence from Clinical Trial Reports. In this study we evaluate various Large Language Models (LLMs) with multiple strategies including Chain-of-Thought In-Context Learning and Parameter-Efficient Fine-Tuning (PEFT). We propose a PEFT method to improve the consistency of LLMs by merging adapters that were fine-tuned separately using triplet and language modelling objectives. We found that merging the two PEFT adapters improves the F1 score (+0.0346) and consistency (+0.152) of the LLMs. However our novel methods did not produce more accurate results than GPT-4 in terms of faithfulness and consistency. Averaging the three metrics GPT-4 ranks joint-first in the competition with 0.8328. Finally our contamination analysis with GPT-4 indicates that there was no test data leakage.
