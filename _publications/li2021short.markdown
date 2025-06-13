---
layout: publication
title: 'A Short Study On Compressing Decoder-based Language Models'
authors: Tianda Li, Yassir El Mesbahi, Ivan Kobyzev, Ahmad Rashid, Atif Mahmud, Nithin Anchuri, Habib Hajimolahoseini, Yang Liu, Mehdi Rezagholizadeh
conference: "Arxiv"
year: 2021
bibkey: li2021short
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08460"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'BERT', 'Distillation']
---
Pre-trained Language Models (PLMs) have been successful for a wide range of
natural language processing (NLP) tasks. The state-of-the-art of PLMs, however,
are extremely large to be used on edge devices. As a result, the topic of model
compression has attracted increasing attention in the NLP community. Most of
the existing works focus on compressing encoder-based models (tiny-BERT,
distilBERT, distilRoBERTa, etc), however, to the best of our knowledge, the
compression of decoder-based models (such as GPT-2) has not been investigated
much. Our paper aims to fill this gap. Specifically, we explore two directions:
1) we employ current state-of-the-art knowledge distillation techniques to
improve fine-tuning of DistilGPT-2. 2) we pre-train a compressed GPT-2 model
using layer truncation and compare it against the distillation-based method
(DistilGPT2). The training time of our compressed model is significantly less
than DistilGPT-2, but it can achieve better performance when fine-tuned on
downstream tasks. We also demonstrate the impact of data cleaning on model
performance.
