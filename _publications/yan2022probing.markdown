---
layout: publication
title: 'Probing Causes Of Hallucinations In Neural Machine Translations'
authors: Yan Jianhao, Meng Fandong, Zhou Jie
conference: "Arxiv"
year: 2022
bibkey: yan2022probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.12529"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture']
---
Hallucination, one kind of pathological translations that bothers Neural Machine Translation, has recently drawn much attention. In simple terms, hallucinated translations are fluent sentences but barely related to source inputs. Arguably, it remains an open problem how hallucination occurs. In this paper, we propose to use probing methods to investigate the causes of hallucinations from the perspective of model architecture, aiming to avoid such problems in future architecture designs. By conducting experiments over various NMT datasets, we find that hallucination is often accompanied by the deficient encoder, especially embeddings, and vulnerable cross-attentions, while, interestingly, cross-attention mitigates some errors caused by the encoder.
