---
layout: publication
title: Fie: Building A Global Probability Space By Leveraging Early Fusion In Encoder For Open-domain Question Answering
authors: Kedia Akhil, Zaidi Mohd Abbas, Lee Haejun
conference: "Arxiv"
year: 2022
bibkey: kedia2022building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.10147"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Generative models have recently started to outperform extractive models in Open Domain Question Answering largely by leveraging their decoder to attend over multiple encoded passages and combining their information. However generative models tend to be larger than extractive models due to the need for a decoder run slower during inference due to auto-regressive decoder beam search and their generated output often suffers from hallucinations. We propose to extend transformer encoders with the ability to fuse information from multiple passages using global representation to provide cross-sample attention over all tokens across samples. Furthermore we propose an alternative answer span probability calculation to better aggregate answer scores in the global space of all samples. Using our proposed method we outperform the current state-of-the-art method by 2.5 Exact Match score on the Natural Question dataset while using only 2537; of parameters and 3537; of the latency during inference and 4.4 Exact Match on WebQuestions dataset. When coupled with synthetic data augmentation we outperform larger models on the TriviaQA dataset as well. The latency and parameter savings of our method make it particularly attractive for open-domain question answering as these models are often compute-intensive.
