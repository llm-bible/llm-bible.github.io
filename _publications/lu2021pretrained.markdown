---
layout: publication
title: Pretrained Transformers as Universal Computation Engines
authors: Lu Kevin, Grover Aditya, Abbeel Pieter, Mordatch Igor
conference: "Arxiv"
year: 2021
bibkey: lu2021pretrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.05247"}
tags: ['ARXIV', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We investigate the capability of a transformer pretrained on natural language to generalize to other modalities with minimal finetuning -- in particular without finetuning of the self-attention and feedforward layers of the residual blocks. We consider such a model which we call a Frozen Pretrained Transformer (FPT) and study finetuning it on a variety of sequence classification tasks spanning numerical computation vision and protein fold prediction. In contrast to prior works which investigate finetuning on the same modality as the pretraining dataset we show that pretraining on natural language can improve performance and compute efficiency on non-language downstream tasks. Additionally we perform an analysis of the architecture comparing the performance of a random initialized transformer to a random LSTM. Combining the two insights we find language-pretrained transformers can obtain strong performance on a variety of non-language tasks.
