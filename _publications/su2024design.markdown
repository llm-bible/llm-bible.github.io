---
layout: publication
title: 'Design As Desired: Utilizing Visual Question Answering For Multimodal Pre-training'
authors: Tongkun Su, Jun Li, Xi Zhang, Haibo Jin, Hao Chen, Qiong Wang, Faqin Lv, Baoliang Zhao, Yin Hu
conference: "Arxiv"
year: 2024
bibkey: su2024design
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00226"}
  - {name: "Code", url: "https://github.com/MoramiSu/QFT-MICCAI2024"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code', 'Pre-Training', 'Applications']
---
Multimodal pre-training demonstrates its potential in the medical domain,
which learns medical visual representations from paired medical reports.
However, many pre-training tasks require extra annotations from clinicians, and
most of them fail to explicitly guide the model to learn the desired features
of different pathologies. In this paper, we utilize Visual Question Answering
(VQA) for multimodal pre-training to guide the framework focusing on targeted
pathological features. We leverage descriptions in medical reports to design
multi-granular question-answer pairs associated with different diseases, which
assist the framework in pre-training without requiring extra annotations from
experts. We also propose a novel pre-training framework with a quasi-textual
feature transformer, a module designed to transform visual features into a
quasi-textual space closer to the textual domain via a contrastive learning
strategy. This narrows the vision-language gap and facilitates modality
alignment. Our framework is applied to four downstream tasks: report
generation, classification, segmentation, and detection across five datasets.
Extensive experiments demonstrate the superiority of our framework compared to
other state-of-the-art methods. Our code is available at
https://github.com/MoramiSu/QFT-MICCAI2024.
