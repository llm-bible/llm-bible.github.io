---
layout: publication
title: 'Quality Or Quantity? On Data Scale And Diversity In Adapting Large Language Models For Low-resource Translation'
authors: Vivek Iyer, Bhavitvya Malik, Pavel Stepachev, Pinzhen Chen, Barry Haddow, Alexandra Birch
conference: "Arxiv"
year: 2024
bibkey: iyer2024quality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12780"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
Despite the recent popularity of Large Language Models (LLMs) in Machine
Translation (MT), their performance in low-resource languages (LRLs) still lags
significantly behind Neural Machine Translation (NMT) models. In this work, we
explore what it would take to adapt LLMs for the low-resource setting.
Particularly, we re-examine the role of two factors: a) the importance and
application of parallel data, and b) diversity in Supervised Fine-Tuning (SFT).
Recently, parallel data has seen reduced use in adapting LLMs for MT, while
data diversity has been embraced to promote transfer across languages and
tasks. However, for low-resource LLM-MT, we show that the opposite is true for
both considerations: a) parallel data is critical during both pre-training and
SFT; b) diversity tends to cause interference instead of transfer. Our
experiments with three LLMs across two low-resourced language groups --
Indigenous American and North-East Indian -- reveal consistent trends,
underscoring the generalizability of our findings. We believe these insights
will be valuable for scaling to massively multilingual LLM-MT models that can
effectively serve LRLs.
