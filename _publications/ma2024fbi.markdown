---
layout: publication
title: FBI45;LLM Scaling Up Fully Binarized Llms From Scratch Via Autoregressive Distillation
authors: Ma Liqun, Sun Mingjie, Shen Zhiqiang
conference: "Arxiv"
year: 2024
bibkey: ma2024fbi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07093"}
  - {name: "Code", url: "https://github.com/LiqunMa/FBI&#45;LLM"}
  - {name: "Code", url: "https://huggingface.co/LiqunMa/)"}
tags: ['Distillation', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
This work presents a Fully BInarized Large Language Model (FBI45;LLM) demonstrating for the first time how to train a large45;scale binary language model from scratch (not the partial binary or ternary LLM like BitNet b1.58) to match the performance of its full45;precision counterparts (e.g. FP16 or BF16) in transformer45;based LLMs. It achieves this by employing an autoregressive distillation (AD) loss with maintaining equivalent model dimensions (130M 1.3B 7B) and training data volume as regular LLM pretraining while delivering competitive results in terms of perplexity and task45;specific effectiveness. Intriguingly by analyzing the training trajectory we find that the pretrained weight is not necessary for training binarized LLMs from scratch. This research encourages a new computational framework and may facilitate the future design of specialized hardware tailored for fully 145;bit LLMs. We make all models code and training dataset fully accessible and transparent to support further research (Code https://github.com/LiqunMa/FBI&#45;LLM. Model https://huggingface.co/LiqunMa/).
