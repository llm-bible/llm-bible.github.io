---
layout: publication
title: 'Quadapter: Adapter For GPT-2 Quantization'
authors: Minseop Park, Jaeseong You, Markus Nagel, Simyung Chang
conference: "Arxiv"
year: 2022
bibkey: park2022adapter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.16912"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Quantization', 'Pretraining Methods', 'Transformer', 'Fine-Tuning']
---
Transformer language models such as GPT-2 are difficult to quantize because
of outliers in activations leading to a large quantization error. To adapt to
the error, one must use quantization-aware training, which entails a
fine-tuning process based on the dataset and the training pipeline identical to
those for the original model. Pretrained language models, however, often do not
grant access to their datasets and training pipelines, forcing us to rely on
arbitrary ones for fine-tuning. In that case, it is observed that
quantization-aware training overfits the model to the fine-tuning data. For
quantization without overfitting, we introduce a quantization adapter
(Quadapter), a small set of parameters that are learned to make activations
quantization-friendly by scaling them channel-wise. It keeps the model
parameters unchanged. By applying our method to the challenging task of
quantizing GPT-2, we demonstrate that it effectively prevents the overfitting
and improves the quantization performance.
