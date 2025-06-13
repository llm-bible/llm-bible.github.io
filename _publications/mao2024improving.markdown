---
layout: publication
title: 'LIFT: Improving Long Context Understanding Through Long Input Fine-tuning'
authors: Yansheng Mao, Jiaqi Li, Fanxu Meng, Jing Xiong, Zilong Zheng, Muhan Zhang
conference: "Arxiv"
year: 2024
bibkey: mao2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13626"}
tags: ['Fine-Tuning', 'Tools', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Long context understanding remains challenging for large language models due
to their limited context windows. This paper introduces Long Input Fine-Tuning
(LIFT) for long context modeling, a novel framework that enhances LLM
performance on long-context tasks by adapting model parameters to the context
at test time. LIFT enables efficient processing of lengthy inputs without the
computational burden of offline long-context adaptation, and can improve the
long-context capabilities of arbitrary short-context models. The framework is
further enhanced by integrating in-context learning and pre-LIFT supervised
fine-tuning. The combination of in-context learning and LIFT enables
short-context models like Llama 3 to handle arbitrarily long contexts and
consistently improves their performance on popular long-context benchmarks like
LooGLE and LongBench. We also provide a comprehensive analysis of the strengths
and limitations of LIFT on long context understanding, offering valuable
directions for future research.
