---
layout: publication
title: 'Revisiting Intermediate Layer Distillation For Compressing Language Models: An Overfitting Perspective'
authors: Jongwoo Ko, Seungjoon Park, Minchan Jeong, Sukjin Hong, Euijai Ahn, Du-seong Chang, Se-young Yun
conference: "Arxiv"
year: 2023
bibkey: ko2023revisiting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2302.01530'}
  - {name: "Code", url: 'https://github.com/jongwooko/CR-ILD'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'BERT', 'Model Architecture', 'Pretraining Methods']
---
Knowledge distillation (KD) is a highly promising method for mitigating the
computational problems of pre-trained language models (PLMs). Among various KD
approaches, Intermediate Layer Distillation (ILD) has been a de facto standard
KD method with its performance efficacy in the NLP field. In this paper, we
find that existing ILD methods are prone to overfitting to training datasets,
although these methods transfer more information than the original KD. Next, we
present the simple observations to mitigate the overfitting of ILD: distilling
only the last Transformer layer and conducting ILD on supplementary tasks.
Based on our two findings, we propose a simple yet effective
consistency-regularized ILD (CR-ILD), which prevents the student model from
overfitting the training dataset. Substantial experiments on distilling BERT on
the GLUE benchmark and several synthetic datasets demonstrate that our proposed
ILD method outperforms other KD techniques. Our code is available at
https://github.com/jongwooko/CR-ILD.
