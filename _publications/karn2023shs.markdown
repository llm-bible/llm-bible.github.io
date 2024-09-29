---
layout: publication
title: shs-nlp at RadSum23 Domain-Adaptive Pre-training of Instruction-tuned LLMs for Radiology Report Impression Generation
authors: Karn Sanjeev Kumar, Ghosh Rikhiya, P Kusuma, Farri Oladimeji
conference: "BioNLP"
year: 2023
bibkey: karn2023shs
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03264"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Instruction-tuned generative Large language models (LLMs) like ChatGPT and Bloomz possess excellent generalization abilities but they face limitations in understanding radiology reports particularly in the task of generating the IMPRESSIONS section from the FINDINGS section. They tend to generate either verbose or incomplete IMPRESSIONS mainly due to insufficient exposure to medical text data during training. We present a system which leverages large-scale medical text data for domain-adaptive pre-training of instruction-tuned LLMs to enhance its medical knowledge and performance on specific medical tasks. We show that this system performs better in a zero-shot setting than a number of pretrain-and-finetune adaptation methods on the IMPRESSIONS generation task and ranks 1st among participating systems in Task 1B Radiology Report Summarization at the BioNLP 2023 workshop.
