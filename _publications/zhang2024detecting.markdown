---
layout: publication
title: 'PIP: Detecting Adversarial Examples In Large Vision-language Models Via Attention Patterns Of Irrelevant Probe Questions'
authors: Yudong Zhang, Ruobing Xie, Jiansheng Chen, Xingwu Sun, Yu Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024detecting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.05076'}
  - {name: "Code", url: 'https://github.com/btzyd/pip'}
tags: ['Attention Mechanism', 'Has Code', 'Security', 'Model Architecture', 'Tools', 'Multimodal Models', 'Responsible AI']
---
Large Vision-Language Models (LVLMs) have demonstrated their powerful
multimodal capabilities. However, they also face serious safety problems, as
adversaries can induce robustness issues in LVLMs through the use of
well-designed adversarial examples. Therefore, LVLMs are in urgent need of
detection tools for adversarial examples to prevent incorrect responses. In
this work, we first discover that LVLMs exhibit regular attention patterns for
clean images when presented with probe questions. We propose an unconventional
method named PIP, which utilizes the attention patterns of one randomly
selected irrelevant probe question (e.g., "Is there a clock?") to distinguish
adversarial examples from clean examples. Regardless of the image to be tested
and its corresponding question, PIP only needs to perform one additional
inference of the image to be tested and the probe question, and then achieves
successful detection of adversarial examples. Even under black-box attacks and
open dataset scenarios, our PIP, coupled with a simple SVM, still achieves more
than 98% recall and a precision of over 90%. Our PIP is the first attempt to
detect adversarial attacks on LVLMs via simple irrelevant probe questions,
shedding light on deeper understanding and introspection within LVLMs. The code
is available at https://github.com/btzyd/pip.
