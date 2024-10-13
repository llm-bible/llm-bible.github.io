---
layout: publication
title: 'Improving Non-autoregressive Generation With Mixup Training'
authors: Jiang Ting, Huang Shaohan, Zhang Zihan, Wang Deqing, Zhuang Fuzhen, Wei Furu, Huang Haizhen, Zhang Liangjie, Zhang Qi
conference: "Arxiv"
year: 2021
bibkey: jiang2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.11115"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
While pre-trained language models have achieved great success on various
natural language understanding tasks, how to effectively leverage them into
non-autoregressive generation tasks remains a challenge. To solve this problem,
we present a non-autoregressive generation model based on pre-trained
transformer models. To bridge the gap between autoregressive and
non-autoregressive models, we propose a simple and effective iterative training
method called MIx Source and pseudo Target (MIST). Unlike other iterative
decoding methods, which sacrifice the inference speed to achieve better
performance based on multiple decoding iterations, MIST works in the training
stage and has no effect on inference time. Our experiments on three generation
benchmarks including question generation, summarization and paraphrase
generation, show that the proposed framework achieves the new state-of-the-art
results for fully non-autoregressive models. We also demonstrate that our
method can be used to a variety of pre-trained models. For instance, MIST based
on the small pre-trained model also obtains comparable performance with seq2seq
models.
