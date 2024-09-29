---
layout: publication
title: Fastseq Make Sequence Generation Faster
authors: Yan Yu, Hu Fei, Chen Jiusheng, Bhendawade Nikhil, Ye Ting, Gong Yeyun, Duan Nan, Cui Desheng, Chi Bingyu, Zhang Ruofei
conference: "Arxiv"
year: 2021
bibkey: yan2021make
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.04718"}
  - {name: "Code", url: "https://github.com/microsoft/fastseq"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Transformer45;based models have made tremendous impacts in natural language generation. However the inference speed is a bottleneck due to large model size and intensive computing involved in auto45;regressive decoding process. We develop FastSeq framework to accelerate sequence generation without accuracy loss. The proposed optimization techniques include an attention cache optimization an efficient algorithm for detecting repeated n45;grams and an asynchronous generation pipeline with parallel I/O. These optimizations are general enough to be applicable to Transformer45;based models (e.g. T5 GPT2 and UniLM). Our benchmark results on a set of widely used and diverse models demonstrate 445;9x inference speed gain. Additionally FastSeq is easy to use with a simple one45;line code change. The source code is available at https://github.com/microsoft/fastseq.
