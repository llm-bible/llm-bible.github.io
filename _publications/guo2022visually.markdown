---
layout: publication
title: Visually-augmented pretrained language models for NLP tasks without images
authors: Guo Hangyu, Zhou Kun, Zhao Wayne Xin, Zhang Qinyu, Wen Ji-rong
conference: "Arxiv"
year: 2022
bibkey: guo2022visually
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.07937"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Although pre-trained language models~(PLMs) have shown impressive performance by text-only self-supervised training they are found lack of visual semantics or commonsense. Existing solutions often rely on explicit images for visual knowledge augmentation (requiring time-consuming retrieval or generation) and they also conduct the augmentation for the whole input text without considering whether it is actually needed in specific inputs or tasks. To address these issues we propose a novel isually-ugmented fine-tuning approach that can be generally applied to various PLMs or NLP tasks ithout using any retrieved or generated mages namely . Experimental results show that our approach can consistently improve the performance of BERT RoBERTa BART and T5 at different scales and outperform several competitive baselines on ten tasks. Our codes and data are publicly available at~.
