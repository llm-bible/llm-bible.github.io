---
layout: publication
title: 'SF2T: Self-supervised Fragment Finetuning Of Video-llms For Fine-grained Understanding'
authors: Yangliu Hu, Zikai Song, Na Feng, Yawei Luo, Junqing Yu, Yi-ping Phoebe Chen, Wei Yang
conference: "Arxiv"
year: 2025
bibkey: hu2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07745'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Video-based Large Language Models (Video-LLMs) have witnessed substantial
advancements in recent years, propelled by the advancement in multi-modal LLMs.
Although these models have demonstrated proficiency in providing the overall
description of videos, they struggle with fine-grained understanding,
particularly in aspects such as visual dynamics and video details inquiries. To
tackle these shortcomings, we find that fine-tuning Video-LLMs on
self-supervised fragment tasks, greatly improve their fine-grained video
understanding abilities. Hence we propose two key contributions:(1)
Self-Supervised Fragment Fine-Tuning (SF\\(^2\\)T), a novel effortless fine-tuning
method, employs the rich inherent characteristics of videos for training, while
unlocking more fine-grained understanding ability of Video-LLMs. Moreover, it
relieves researchers from labor-intensive annotations and smartly circumvents
the limitations of natural language, which often fails to capture the complex
spatiotemporal variations in videos; (2) A novel benchmark dataset, namely
FineVidBench, for rigorously assessing Video-LLMs' performance at both the
scene and fragment levels, offering a comprehensive evaluation of their
capabilities. We assessed multiple models and validated the effectiveness of
SF\\(^2\\)T on them. Experimental results reveal that our approach improves their
ability to capture and interpret spatiotemporal details.
