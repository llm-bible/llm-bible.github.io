---
layout: publication
title: "Token Drop Mechanism For Neural Machine Translation"
authors: Zhang Huaao, Qiu Shigui, Duan Xiangyu, Zhang Min
conference: "Arxiv"
year: 2020
bibkey: zhang2020token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.11018"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Neural machine translation with millions of parameters is vulnerable to unfamiliar inputs. We propose Token Drop to improve generalization and avoid overfitting for the NMT model. Similar to word dropout whereas we replace dropped token with a special token instead of setting zero to words. We further introduce two self-supervised objectives Replaced Token Detection and Dropped Token Prediction. Our method aims to force model generating target translation with less information in this way the model can learn textual representation better. Experiments on Chinese-English and English-Romanian benchmark demonstrate the effectiveness of our approach and our model achieves significant improvements over a strong Transformer baseline.
