---
layout: publication
title: Mixsumm Topic45;based Data Augmentation Using Llms For Low45;resource Extractive Text Summarization
authors: Sahu Gaurav, Laradji Issam H.
conference: "Arxiv"
year: 2024
bibkey: sahu2024topic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07341"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Low45;resource extractive text summarization is a vital but heavily underexplored area of research. Prior literature either focuses on abstractive text summarization or prompts a large language model (LLM) like GPT45;3 directly to generate summaries. In this work we propose MixSumm for low45;resource extractive text summarization. Specifically MixSumm prompts an open45;source LLM LLaMA45;345;70b to generate documents that mix information from multiple topics as opposed to generating documents without mixup and then trains a summarization model on the generated dataset. We use ROUGE scores and L45;Eval a reference45;free LLaMA45;345;based evaluation method to measure the quality of generated summaries. We conduct extensive experiments on a challenging text summarization benchmark comprising the TweetSumm WikiHow and ArXiv/PubMed datasets and show that our LLM45;based data augmentation framework outperforms recent prompt45;based approaches for low45;resource extractive summarization. Additionally our results also demonstrate effective knowledge distillation from LLaMA45;345;70b to a small BERT45;based extractive summarizer.
