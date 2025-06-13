---
layout: publication
title: 'Visual Transformation Telling'
authors: Wanqing Cui, Xin Hong, Yanyan Lan, Liang Pang, Jiafeng Guo, Xueqi Cheng
conference: "Arxiv"
year: 2023
bibkey: cui2023visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.01928'}
tags: ['GPT', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
Humans can naturally reason from superficial state differences (e.g. ground
wetness) to transformations descriptions (e.g. raining) according to their life
experience. In this paper, we propose a new visual reasoning task to test this
transformation reasoning ability in real-world scenarios, called
\textbf\{V\}isual \textbf\{T\}ransformation \textbf\{T\}elling (VTT). Given a series
of states (i.e. images), VTT requires to describe the transformation occurring
between every two adjacent states. Different from existing visual reasoning
tasks that focus on surface state reasoning, the advantage of VTT is that it
captures the underlying causes, e.g. actions or events, behind the differences
among states. We collect a novel dataset to support the study of transformation
reasoning from two existing instructional video datasets, CrossTask and COIN,
comprising 13,547 samples. Each sample involves the key state images along with
their transformation descriptions. Our dataset covers diverse real-world
activities, providing a rich resource for training and evaluation. To construct
an initial benchmark for VTT, we test several models, including traditional
visual storytelling methods (CST, GLACNet, Densecap) and advanced multimodal
large language models (LLaVA v1.5-7B, Qwen-VL-chat, Gemini Pro Vision, GPT-4o,
and GPT-4). Experimental results reveal that even state-of-the-art models still
face challenges in VTT, highlighting substantial areas for improvement.
