---
layout: publication
title: 'Understanding And Improving Sequence-to-sequence Pretraining For Neural Machine Translation'
authors: Wang Wenxuan, Jiao Wenxiang, Hao Yongchang, Wang Xing, Shi Shuming, Tu Zhaopeng, Lyu Michael
conference: "Arxiv"
year: 2022
bibkey: wang2022understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.08442"}
tags: ['Applications', 'Pretraining Methods', 'Security', 'Training Techniques']
---
"In this paper, we present a substantial step in better understanding the SOTA sequence-to-sequence (Seq2Seq) pretraining for neural machine translation~(NMT). We focus on studying the impact of the jointly pretrained decoder, which is the main difference between Seq2Seq pretraining and previous encoder-based pretraining approaches for NMT. By carefully designing experiments on three language pairs, we find that Seq2Seq pretraining is a double-edged sword: On one hand, it helps NMT models to produce more diverse translations and reduce adequacy-related translation errors. On the other hand, the discrepancies between Seq2Seq pretraining and NMT finetuning limit the translation quality (i.e., domain discrepancy) and induce the over-estimation issue (i.e., objective discrepancy). Based on these observations, we further propose simple and effective strategies, named in-domain pretraining and input adaptation to remedy the domain and objective discrepancies, respectively. Experimental results on several language pairs show that our approach can consistently improve both translation performance and model robustness upon Seq2Seq pretraining."
