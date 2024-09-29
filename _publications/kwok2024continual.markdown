---
layout: publication
title: Continual Learning Optimizations For Auto-regressive Decoder Of Multilingual ASR Systems
authors: Kwok Chin Yuen, Yip Jia Qi, Chng Eng Siong
conference: "Arxiv"
year: 2024
bibkey: kwok2024continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03645"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Continual Learning (CL) involves fine-tuning pre-trained models with new data while maintaining the performance on the pre-trained data. This is particularly relevant for expanding multilingual ASR (MASR) capabilities. However existing CL methods mainly designed for computer vision and reinforcement learning tasks often yield sub-optimal results when directly applied to MASR. We hypothesise that this is because CL of the auto-regressive decoder in the MASR model is difficult. To verify this we propose four optimizations on the decoder. They include decoder-layer gradient surgery freezing unused token embeddings suppressing output of newly added tokens and learning rate re-scaling. Our experiments on adapting Whisper to 10 unseen languages from the Common Voice dataset demonstrate that these optimizations reduce the Average Word Error Rate (AWER) of pretrained languages from 14.237; to 12.437; compared with Experience Replay without compromising the AWER of new languages.
