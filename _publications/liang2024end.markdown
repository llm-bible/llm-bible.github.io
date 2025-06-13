---
layout: publication
title: 'Thames: An End-to-end Tool For Hallucination Mitigation And Evaluation In Large Language Models'
authors: Mengfei Liang, Archish Arun, Zekun Wu, Cristian Munoz, Jonathan Lutch, Emre Kazim, Adriano Koshiyama, Philip Treleaven
conference: "NeurIPS Workshop on Socially Responsible Language Modelling Research 2024"
year: 2024
bibkey: liang2024end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11353"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Hallucination, the generation of factually incorrect content, is a growing
challenge in Large Language Models (LLMs). Existing detection and mitigation
methods are often isolated and insufficient for domain-specific needs, lacking
a standardized pipeline. This paper introduces THaMES (Tool for Hallucination
Mitigations and EvaluationS), an integrated framework and library addressing
this gap. THaMES offers an end-to-end solution for evaluating and mitigating
hallucinations in LLMs, featuring automated test set generation, multifaceted
benchmarking, and adaptable mitigation strategies. It automates test set
creation from any corpus, ensuring high data quality, diversity, and
cost-efficiency through techniques like batch processing, weighted sampling,
and counterfactual validation. THaMES assesses a model's ability to detect and
reduce hallucinations across various tasks, including text generation and
binary classification, applying optimal mitigation strategies like In-Context
Learning (ICL), Retrieval Augmented Generation (RAG), and Parameter-Efficient
Fine-tuning (PEFT). Evaluations of state-of-the-art LLMs using a knowledge base
of academic papers, political news, and Wikipedia reveal that commercial models
like GPT-4o benefit more from RAG than ICL, while open-weight models like
Llama-3.1-8B-Instruct and Mistral-Nemo gain more from ICL. Additionally, PEFT
significantly enhances the performance of Llama-3.1-8B-Instruct in both
evaluation tasks.
