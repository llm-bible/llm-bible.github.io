---
layout: publication
title: 'Incorporating Probing Signals Into Multimodal Machine Translation Via Visual Question-answering Pairs'
authors: Yuxin Zuo, Bei Li, Chuanhao Lv, Tong Zheng, Tong Xiao, Jingbo Zhu
conference: "Arxiv"
year: 2023
bibkey: zuo2023incorporating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17133"}
  - {name: "Code", url: "https://github.com/libeineu/MMT-VQA"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Has Code', 'Applications']
---
This paper presents an in-depth study of multimodal machine translation
(MMT), examining the prevailing understanding that MMT systems exhibit
decreased sensitivity to visual information when text inputs are complete.
Instead, we attribute this phenomenon to insufficient cross-modal interaction,
rather than image information redundancy. A novel approach is proposed to
generate parallel Visual Question-Answering (VQA) style pairs from the source
text, fostering more robust cross-modal interaction. Using Large Language
Models (LLMs), we explicitly model the probing signal in MMT to convert it into
VQA-style data to create the Multi30K-VQA dataset. An MMT-VQA multitask
learning framework is introduced to incorporate explicit probing signals from
the dataset into the MMT training process. Experimental results on two
widely-used benchmarks demonstrate the effectiveness of this novel approach.
Our code and data would be available at:
\url\{https://github.com/libeineu/MMT-VQA\}.
