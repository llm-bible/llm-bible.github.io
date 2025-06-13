---
layout: publication
title: 'Distilling Fine-grained Sentiment Understanding From Large Language Models'
authors: Yice Zhang, Guangyu Xie, Hongling Xu, Kaiheng Hou, Jianzhu Bao, Qianlong Wang, Shiwei Chen, Ruifeng Xu
conference: "Arxiv"
year: 2024
bibkey: zhang2024distilling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.18552'}
  - {name: "Code", url: 'https://github.com/HITSZ-HLT/FSA-Distillation'}
tags: ['Has Code', 'Efficiency and Optimization', 'Distillation', 'Applications', 'Prompting']
---
Fine-grained sentiment analysis (FSA) aims to extract and summarize user
opinions from vast opinionated text. Recent studies demonstrate that large
language models (LLMs) possess exceptional sentiment understanding
capabilities. However, directly deploying LLMs for FSA applications incurs high
inference costs. Therefore, this paper investigates the distillation of
fine-grained sentiment understanding from LLMs into small language models
(SLMs). We prompt LLMs to examine and interpret the sentiments of given reviews
and then utilize the generated content to pretrain SLMs. Additionally, we
develop a comprehensive FSA benchmark to evaluate both SLMs and LLMs. Extensive
experiments on this benchmark reveal that: (1) distillation significantly
enhances the performance of SLMs in FSA tasks, achieving a 6.00% improvement
in \\(F_1\\)-score, and the distilled model can outperform Llama-2-7b with only
220M parameters; (2) distillation equips SLMs with excellent zero-shot
sentiment classification capabilities, enabling them to match or even exceed
their teacher models. These results suggest that distillation from LLMs is a
highly promising direction for FSA. We will release our code, data, and
pretrained model weights at https://github.com/HITSZ-HLT/FSA-Distillation.
