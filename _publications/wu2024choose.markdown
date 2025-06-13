---
layout: publication
title: 'Choose The Final Translation From NMT And LLM Hypotheses Using MBR Decoding: Hw-tsc''s Submission To The WMT24 General MT Shared Task'
authors: Zhanglin Wu, Daimeng Wei, Zongyao Li, Hengchao Shang, Jiaxin Guo, Shaojun Li, Zhiqiang Rao, Yuanchang Luo, Ning Xie, Hao Yang
conference: "Arxiv"
year: 2024
bibkey: wu2024choose
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14800"}
tags: ['WMT', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Pre-Training', 'Applications']
---
This paper presents the submission of Huawei Translate Services Center
(HW-TSC) to the WMT24 general machine translation (MT) shared task, where we
participate in the English to Chinese (en2zh) language pair. Similar to
previous years' work, we use training strategies such as regularized dropout,
bidirectional training, data diversification, forward translation, back
translation, alternated training, curriculum learning, and transductive
ensemble learning to train the neural machine translation (NMT) model based on
the deep Transformer-big architecture. The difference is that we also use
continue pre-training, supervised fine-tuning, and contrastive preference
optimization to train the large language model (LLM) based MT model. By using
Minimum Bayesian risk (MBR) decoding to select the final translation from
multiple hypotheses for NMT and LLM-based MT models, our submission receives
competitive results in the final evaluation.
