---
layout: publication
title: 'Learning From Models Beyond Fine-tuning'
authors: Hongling Zheng, Li Shen, Anke Tang, Yong Luo, Han Hu, Bo Du, Yonggang Wen, Dacheng Tao
conference: "Nat Mach Intell 7 6-17 (2025)"
year: 2023
bibkey: zheng2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08184"}
  - {name: "Code", url: "https://github.com/ruthless-man/Awesome-Learn-from-Model"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Survey Paper', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
Foundation models (FM) have demonstrated remarkable performance across a wide
range of tasks (especially in the fields of natural language processing and
computer vision), primarily attributed to their ability to comprehend
instructions and access extensive, high-quality data. This not only showcases
their current effectiveness but also sets a promising trajectory towards the
development of artificial general intelligence. Unfortunately, due to multiple
constraints, the raw data of the model used for large model training are often
inaccessible, so the use of end-to-end models for downstream tasks has become a
new research trend, which we call Learn From Model (LFM) in this article. LFM
focuses on the research, modification, and design of FM based on the model
interface, so as to better understand the model structure and weights (in a
black box environment), and to generalize the model to downstream tasks. The
study of LFM techniques can be broadly categorized into five major areas: model
tuning, model distillation, model reuse, meta learning and model editing. Each
category encompasses a repertoire of methods and strategies that aim to enhance
the capabilities and performance of FM. This paper gives a comprehensive review
of the current methods based on FM from the perspective of LFM, in order to
help readers better understand the current research status and ideas. To
conclude, we summarize the survey by highlighting several critical areas for
future exploration and addressing open issues that require further attention
from the research community. The relevant papers we investigated in this
article can be accessed at
https://github.com/ruthless-man/Awesome-Learn-from-Model
