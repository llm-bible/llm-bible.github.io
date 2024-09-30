---
layout: publication
title: 'Efficient Continual Pre-training By Mitigating The Stability Gap'
authors: Guo Yiduo, Fu Jie, Zhang Huishuai, Zhao Dongyan, Shen Yikang
conference: "Arxiv"
year: 2024
bibkey: guo2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14833"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Continual pre-training has increasingly become the predominant approach for adapting Large Language Models (LLMs) to new domains. This process involves updating the pre-trained LLM with a corpus from a new domain resulting in a shift in the training distribution. To study the behavior of LLMs during this shift we measured the models performance throughout the continual pre-training process. we observed a temporary performance drop at the beginning followed by a recovery phase a phenomenon known as the stability gap previously noted in vision models classifying new classes. To address this issue and enhance LLM performance within a fixed compute budget we propose three effective strategies (1) Continually pre-training the LLM on a subset with a proper size for multiple epochs resulting in faster performance recovery than pre-training the LLM on a large corpus in a single epoch; (2) Pre-training the LLM only on high-quality sub-corpus which rapidly boosts domain performance; and (3) Using a data mixture similar to the pre-training data to reduce distribution gap. We conduct various experiments on Llama-family models to validate the effectiveness of our strategies in both medical continual pre-training and instruction tuning. For example our strategies improve the average medical task performance of the OpenLlama-3B model from 36.237; to 40.737; with only 4037; of the original training budget and enhance the average general task performance without causing forgetting. Furthermore we apply our strategies to the Llama-3-8B model. The resulting model Llama-3-Physician achieves the best medical performance among current open-source models and performs comparably to or even better than GPT-4 on several medical benchmarks. We release our models at urlhttps://huggingface.co/YiDuo1999/Llama-3-Physician-8B-Instruct\}."
