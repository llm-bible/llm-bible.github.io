---
layout: publication
title: 'Efficient Multi-modal Large Language Models Via Visual Token Grouping'
authors: Minbin Huang, Runhui Huang, Han Shi, Yimeng Chen, Chuanyang Zheng, Xiangguo Sun, Xin Jiang, Zhenguo Li, Hong Cheng
conference: "Arxiv"
year: 2024
bibkey: huang2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17773"}
tags: ['RAG', 'Attention Mechanism', 'Model Architecture', 'Applications']
---
The development of Multi-modal Large Language Models (MLLMs) enhances Large
Language Models (LLMs) with the ability to perceive data formats beyond text,
significantly advancing a range of downstream applications, such as visual
question answering and image captioning. However, the substantial computational
costs associated with processing high-resolution images and videos pose a
barrier to their broader adoption. To address this challenge, compressing
vision tokens in MLLMs has emerged as a promising approach to reduce inference
costs. While existing methods conduct token reduction in the feature alignment
phase. In this paper, we introduce VisToG, a novel grouping mechanism that
leverages the capabilities of pre-trained vision encoders to group similar
image segments without the need for segmentation masks. Specifically, we
concatenate semantic tokens to represent image semantic segments after the
linear projection layer before feeding into the vision encoder. Besides, with
the isolated attention we adopt, VisToG can identify and eliminate redundant
visual tokens utilizing the prior knowledge in the pre-trained vision encoder,
which effectively reduces computational demands. Extensive experiments
demonstrate the effectiveness of VisToG, maintaining 98.1% of the original
performance while achieving a reduction of over 27% inference time.
