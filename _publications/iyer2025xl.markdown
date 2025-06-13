---
layout: publication
title: 'Xl-instruct: Synthetic Data For Cross-lingual Open-ended Generation'
authors: Vivek Iyer, Ricardo Rei, Pinzhen Chen, Alexandra Birch
conference: "Arxiv"
year: 2025
bibkey: iyer2025xl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22973"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Cross-lingual open-ended generation -- i.e. generating responses in a desired
language different from that of the user's query -- is an important yet
understudied problem. We introduce XL-AlpacaEval, a new benchmark for
evaluating cross-lingual generation capabilities in Large Language Models
(LLMs), and propose XL-Instruct, a high-quality synthetic data generation
method. Fine-tuning with just 8K XL-Instruct-generated instructions
significantly improves model performance, increasing the win rate against
GPT-4o-Mini from 7.4% to 21.5%, and improving on several fine-grained quality
metrics. Additionally, models fine-tuned on XL-Instruct exhibit strong
zero-shot transfer to both English-only and multilingual generation tasks.
Given its consistent gains across the board, we strongly recommend
incorporating XL-Instruct in the post-training pipeline of future multilingual
LLMs. To facilitate further research, we will publicly and freely release the
XL-Instruct and XL-AlpacaEval datasets, which constitute two of the few
cross-lingual resources currently available in the literature.
