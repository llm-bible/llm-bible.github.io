---
layout: publication
title: 'Improving Non-autoregressive Translation Quality With Pretrained Language Model, Embedding Distillation And Upsampling Strategy For CTC'
authors: Syu Shen-sian, Xie Juncheng, Lee Hung-yi
conference: "Arxiv"
year: 2023
bibkey: syu2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06345"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
"Non-autoregressive approaches aim to improve the inference speed of translation models, particularly those that generate output in a one-pass forward manner. However, these approaches often suffer from a significant drop in translation quality compared to autoregressive models. This paper introduces a series of innovative techniques to enhance the translation quality of Non-Autoregressive Translation (NAT) models while maintaining a substantial acceleration in inference speed. We propose fine-tuning Pretrained Multilingual Language Models (PMLMs) with the CTC loss to train NAT models effectively. Furthermore, we adopt the MASK insertion scheme for up-sampling instead of token duplication, and we present an embedding distillation method to further enhance performance. In our experiments, our model outperforms the baseline autoregressive model (Transformer \textit\{base\}) on multiple datasets, including WMT'14 DE\(\leftrightarrow\)EN, WMT'16 RO\(\leftrightarrow\)EN, and IWSLT'14 DE\(\leftrightarrow\)EN. Notably, our model achieves better performance than the baseline autoregressive model on the IWSLT'14 En\(\leftrightarrow\)De and WMT'16 En\(\leftrightarrow\)Ro datasets, even without using distillation data during training. It is worth highlighting that on the IWSLT'14 DE\(\rightarrow\)EN dataset, our model achieves an impressive BLEU score of 39.59, setting a new state-of-the-art performance. Additionally, our model exhibits a remarkable speed improvement of 16.35 times compared to the autoregressive model."
