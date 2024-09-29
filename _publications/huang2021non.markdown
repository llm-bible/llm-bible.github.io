---
layout: publication
title: 'Non-autoregressive Translation With Layer-wise Prediction And Deep Supervision'
authors: Huang Chenyang, Zhou Hao, Zaïane Osmar R., Mou Lili, Li Lei
conference: "Arxiv"
year: 2021
bibkey: huang2021non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.07515"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
How do we perform efficient inference while retaining high translation quality Existing neural machine translation models such as Transformer achieve high performance but they decode words one by one which is inefficient. Recent non-autoregressive translation models speed up the inference but their quality is still inferior. In this work we propose DSLP a highly efficient and high-performance model for machine translation. The key insight is to train a non-autoregressive Transformer with Deep Supervision and feed additional Layer-wise Predictions. We conducted extensive experiments on four translation tasks (both directions of WMT14 EN-DE and WMT16 EN-RO). Results show that our approach consistently improves the BLEU scores compared with respective base models. Specifically our best variant outperforms the autoregressive model on three translation tasks while being 14.8 times more efficient in inference.
