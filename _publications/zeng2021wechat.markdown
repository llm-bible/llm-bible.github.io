---
layout: publication
title: 'Wechat Neural Machine Translation Systems For WMT21'
authors: Zeng Xianfeng, Liu Yijin, Li Ernan, Ran Qiu, Meng Fandong, Li Peng, Xu Jinan, Zhou Jie
conference: "Arxiv"
year: 2021
bibkey: zeng2021wechat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.02401"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
This paper introduces WeChat AI's participation in WMT 2021 shared news
translation task on English->Chinese, English->Japanese, Japanese->English and
English->German. Our systems are based on the Transformer (Vaswani et al.,
2017) with several novel and effective variants. In our experiments, we employ
data filtering, large-scale synthetic data generation (i.e., back-translation,
knowledge distillation, forward-translation, iterative in-domain knowledge
transfer), advanced finetuning approaches, and boosted Self-BLEU based model
ensemble. Our constrained systems achieve 36.9, 46.9, 27.8 and 31.3
case-sensitive BLEU scores on English->Chinese, English->Japanese,
Japanese->English and English->German, respectively. The BLEU scores of
English->Chinese, English->Japanese and Japanese->English are the highest among
all submissions, and that of English->German is the highest among all
constrained submissions.
