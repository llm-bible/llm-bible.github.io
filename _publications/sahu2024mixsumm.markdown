---
layout: publication
title: MixSumm Topic-based Data Augmentation using LLMs for Low-resource Extractive Text Summarization
authors: Sahu Gaurav, Laradji Issam H.
conference: "Arxiv"
year: 2024
bibkey: sahu2024mixsumm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07341"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Low-resource extractive text summarization is a vital but heavily underexplored area of research. Prior literature either focuses on abstractive text summarization or prompts a large language model (LLM) like GPT-3 directly to generate summaries. In this work we propose MixSumm for low-resource extractive text summarization. Specifically MixSumm prompts an open-source LLM LLaMA-3-70b to generate documents that mix information from multiple topics as opposed to generating documents without mixup and then trains a summarization model on the generated dataset. We use ROUGE scores and L-Eval a reference-free LLaMA-3-based evaluation method to measure the quality of generated summaries. We conduct extensive experiments on a challenging text summarization benchmark comprising the TweetSumm WikiHow and ArXiv/PubMed datasets and show that our LLM-based data augmentation framework outperforms recent prompt-based approaches for low-resource extractive summarization. Additionally our results also demonstrate effective knowledge distillation from LLaMA-3-70b to a small BERT-based extractive summarizer.
