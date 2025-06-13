---
layout: publication
title: 'Unified Autoregressive Visual Generation And Understanding With Continuous Tokens'
authors: Lijie Fan, Luming Tang, Siyang Qin, Tianhong Li, Xuan Yang, Siyuan Qiao, Andreas Steiner, Chen Sun, Yuanzhen Li, Tao Zhu, Michael Rubinstein, Michalis Raptis, Deqing Sun, Radu Soricut
conference: "Arxiv"
year: 2025
bibkey: fan2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13436"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
We present UniFluid, a unified autoregressive framework for joint visual
generation and understanding leveraging continuous visual tokens. Our unified
autoregressive architecture processes multimodal image and text inputs,
generating discrete tokens for text and continuous tokens for image. We find
though there is an inherent trade-off between the image generation and
understanding task, a carefully tuned training recipe enables them to improve
each other. By selecting an appropriate loss balance weight, the unified model
achieves results comparable to or exceeding those of single-task baselines on
both tasks. Furthermore, we demonstrate that employing stronger pre-trained
LLMs and random-order generation during training is important to achieve
high-fidelity image generation within this unified framework. Built upon the
Gemma model series, UniFluid exhibits competitive performance across both image
generation and understanding, demonstrating strong transferability to various
downstream tasks, including image editing for generation, as well as visual
captioning and question answering for understanding.
