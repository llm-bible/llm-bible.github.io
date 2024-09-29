---
layout: publication
title: 'Flacuna: Unleashing The Problem Solving Power Of Vicuna Using FLAN Fine-tuning'
authors: Ghosal Deepanway, Chia Yew Ken, Majumder Navonil, Poria Soujanya
conference: "Arxiv"
year: 2023
bibkey: ghosal2023unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.02053"}
  - {name: "Code", url: "https://huggingface.co/declare-lab/flacuna-13b-v1.0"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Recently the release of INSTRUCTEVAL has provided valuable insights into the performance of large language models (LLMs) that utilize encoder-decoder or decoder-only architecture. Interestingly despite being introduced four years ago T5-based LLMs such as FLAN-T5 continue to outperform the latest decoder-based LLMs such as LLAMA and VICUNA on tasks that require general problem-solving skills. This performance discrepancy can be attributed to three key factors (1) Pre-training data (2) Backbone architecture and (3) Instruction dataset. In this technical report our main focus is on investigating the impact of the third factor by leveraging VICUNA a large language model based on LLAMA which has undergone fine-tuning on ChatGPT conversations. To achieve this objective we fine-tuned VICUNA using a customized instruction dataset collection called FLANMINI. This collection includes a subset of the large-scale instruction dataset known as FLAN as well as various code-related datasets and conversational datasets derived from ChatGPT/GPT-4. This dataset comprises a large number of tasks that demand problem-solving skills. Our experimental findings strongly indicate that the enhanced problem-solving abilities of our model FLACUNA are obtained through fine-tuning VICUNA on the FLAN dataset leading to significant improvements across numerous benchmark datasets in INSTRUCTEVAL. FLACUNA is publicly available at https://huggingface.co/declare-lab/flacuna-13b-v1.0."
