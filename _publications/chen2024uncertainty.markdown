---
layout: publication
title: 'Uncertainty-guided Self-questioning And Answering For Video-language Alignment'
authors: Jin Chen, Kaijing Ma, Haojian Huang, Han Fang, Hao Sun, Mehdi Hosseinzadeh, Zhe Liu
conference: "Arxiv"
year: 2024
bibkey: chen2024uncertainty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02768"}
tags: ['Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
The development of multi-modal models has been rapidly advancing, with some
demonstrating remarkable capabilities. However, annotating video-text pairs
remains expensive and insufficient. Take video question answering (VideoQA)
tasks as an example, human annotated questions and answers often cover only
part of the video, since the corresponding text is often short and monotonous,
leading to underutilization of video. To address this, we propose a
Bootstrapping Video-Language Alignment framework (BoViLA), a self-training
method that augments question samples during training process through LLM-based
self-questioning and answering, which help model exploit video information and
the internal knowledge of LLMs more thoroughly to improve modality alignment.
However, low-quality self-generated questions may instead contaminate the
performance, especially in the early stages of training, as we have observed in
our experiments. To filter bad self-generated questions, we introduce
Evidential Deep Learning (EDL) to estimate uncertainty and assess the quality
of self-generated questions by evaluating the modality alignment within the
context. To the best of our knowledge, this work is the first to explore
LLM-based self-training frameworks for modality alignment. We evaluate BoViLA
on five strong VideoQA benchmarks, where it outperforms several
state-of-the-art methods and demonstrate its effectiveness and generality.
Additionally, we provide extensive analyses of the self-training framework and
the EDL-based uncertainty filtering mechanism. The code will be made available.
