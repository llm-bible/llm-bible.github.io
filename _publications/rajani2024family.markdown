---
layout: publication
title: 'Kodexv0.1: A Family Of State-of-the-art Financial Large Language Models'
authors: Neel Rajani, Lilli Kiessling, Aleksandr Ogaltsov, Claus Lang
conference: "Arxiv"
year: 2024
bibkey: rajani2024family
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13749"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Fine-Tuning', 'Applications']
---
Although powerful, current cutting-edge LLMs may not fulfil the needs of
highly specialised sectors. We introduce KodeXv0.1, a family of large language
models that outclass GPT-4 in financial question answering. We utilise the base
variants of Llama 3.1 8B and 70B and adapt them to the financial domain through
a custom training regime. To this end, we collect and process a large number of
publicly available financial documents such as earnings calls and business
reports. These are used to generate a high-quality, synthetic dataset
consisting of Context-Question-Answer triplets which closely mirror real-world
financial tasks. Using the train split of this dataset, we perform RAG-aware
4bit LoRA instruction tuning runs of Llama 3.1 base variants to produce
KodeX-8Bv0.1 and KodeX-70Bv0.1. We then complete extensive model evaluations
using FinanceBench, FinQABench and the withheld test split of our dataset. Our
results show that KodeX-8Bv0.1 is more reliable in financial contexts than
cutting-edge instruct models in the same parameter regime, surpassing them by
up to 9.24%. In addition, it is even capable of outperforming state-of-the-art
proprietary models such as GPT-4 by up to 7.07%. KodeX-70Bv0.1 represents a
further improvement upon this, exceeding GPT-4's performance on every tested
benchmark.
