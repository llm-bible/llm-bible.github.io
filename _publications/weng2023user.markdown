---
layout: publication
title: 'Lmtuner: An User-friendly And Highly-integrable Training Framework For Fine-tuning Large Language Models'
authors: Yixuan Weng, Zhiqi Wang, Huanxuan Liao, Shizhu He, Shengping Liu, Kang Liu, Jun Zhao
conference: "Arxiv"
year: 2023
bibkey: weng2023user
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10252"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
With the burgeoning development in the realm of large language models (LLMs),
the demand for efficient incremental training tailored to specific industries
and domains continues to increase. Currently, the predominantly employed
frameworks lack modular design, it often takes a lot of coding work to
kickstart the training of LLM. To address this, we present "LMTuner", a highly
usable, integrable, and scalable system for training LLMs expeditiously and
with minimal user-input. LMTuner comprises three main modules - the
Interaction, Training, and Inference Modules. We advocate that LMTuner's
usability and integrality alleviate the complexities in training large language
models. Remarkably, even a novice user could commence training large language
models within five minutes. Furthermore, it integrates DeepSpeed frameworks and
supports Efficient Fine-Tuning methodologies like Low Rank Adaptation (LoRA),
Quantized LoRA (QLoRA), etc., enabling the training of language models scaling
from 300M to a whopping 130B parameters using a single server. The LMTuner's
homepage (https://wengsyx.github.io/LMTuner/)and screencast video
(https://youtu.be/nsXmWOmN3rE) are now publicly available.
