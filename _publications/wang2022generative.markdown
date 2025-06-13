---
layout: publication
title: 'GIT: A Generative Image-to-text Transformer For Vision And Language'
authors: Jianfeng Wang, Zhengyuan Yang, Xiaowei Hu, Linjie Li, Kevin Lin, Zhe Gan, Zicheng Liu, Ce Liu, Lijuan Wang
conference: "Arxiv"
year: 2022
bibkey: wang2022generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.14100"}
  - {name: "Code", url: "https://github.com/microsoft/GenerativeImage2Text"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Has Code', 'Pre-Training']
---
In this paper, we design and train a Generative Image-to-text Transformer,
GIT, to unify vision-language tasks such as image/video captioning and question
answering. While generative models provide a consistent network architecture
between pre-training and fine-tuning, existing work typically contains complex
structures (uni/multi-modal encoder/decoder) and depends on external modules
such as object detectors/taggers and optical character recognition (OCR). In
GIT, we simplify the architecture as one image encoder and one text decoder
under a single language modeling task. We also scale up the pre-training data
and the model size to boost the model performance. Without bells and whistles,
our GIT establishes new state of the arts on 12 challenging benchmarks with a
large margin. For instance, our model surpasses the human performance for the
first time on TextCaps (138.2 vs. 125.5 in CIDEr). Furthermore, we present a
new scheme of generation-based image classification and scene text recognition,
achieving decent performance on standard benchmarks. Codes are released at
\url\{https://github.com/microsoft/GenerativeImage2Text\}.
