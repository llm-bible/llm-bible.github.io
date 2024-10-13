---
layout: publication
title: 'Improving Retrieval Augmented Open-domain Question-answering With Vectorized Contexts'
authors: Chen Zhuo, Wang Xinyu, Jiang Yong, Xie Pengjun, Huang Fei, Tu Kewei
conference: "Arxiv"
year: 2024
bibkey: chen2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02022"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
In the era of large language models, applying techniques such as Retrieval
Augmented Generation can better address Open-Domain Question-Answering
problems. Due to constraints including model sizes and computing resources, the
length of context is often limited, and it becomes challenging to empower the
model to cover overlong contexts while answering questions from open domains.
This paper proposes a general and convenient method to covering longer contexts
in Open-Domain Question-Answering tasks. It leverages a small encoder language
model that effectively encodes contexts, and the encoding applies
cross-attention with origin inputs. With our method, the origin language models
can cover several times longer contexts while keeping the computing
requirements close to the baseline. Our experiments demonstrate that after
fine-tuning, there is improved performance across two held-in datasets, four
held-out datasets, and also in two In Context Learning settings.
