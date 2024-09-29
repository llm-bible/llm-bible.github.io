---
layout: publication
title: 'The Niutrans System For WNGT 2020 Efficiency Task'
authors: Hu Chi, Li Bei, Lin Ye, Li Yinqiao, Li Yanyang, Wang Chenglong, Xiao Tong, Zhu Jingbo
conference: "Arxiv"
year: 2021
bibkey: hu2021niutrans
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.08008"}
  - {name: "Code", url: "https://github.com/NiuTrans/NiuTensor),"}
  - {name: "Code", url: "https://github.com/NiuTrans/NiuTrans.NMT)"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Transformer']
---
This paper describes the submissions of the NiuTrans Team to the WNGT 2020 Efficiency Shared Task. We focus on the efficient implementation of deep Transformer models (cite)wang-etal-2019-learning li-etal-2019-niutrans using NiuTensor (https://github.com/NiuTrans/NiuTensor), a flexible toolkit for NLP tasks. We explored the combination of deep encoder and shallow decoder in Transformer models via model compression and knowledge distillation. The neural machine translation decoding also benefits from FP16 inference attention caching dynamic batching and batch pruning. Our systems achieve promising results in both translation quality and efficiency e.g. our fastest system can translate more than 40000 tokens per second with an RTX 2080 Ti while maintaining 42.9 BLEU on (textitnewstest2018). The code models and docker images are available at NiuTrans.NMT (https://github.com/NiuTrans/NiuTrans.NMT)."
