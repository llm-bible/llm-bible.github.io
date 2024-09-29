---
layout: publication
title: LAVENDER Unifying Video45;language Understanding As Masked Language Modeling
authors: Li Linjie, Gan Zhe, Lin Kevin, Lin Chung-ching, Liu Zicheng, Liu Ce, Wang Lijuan
conference: "Arxiv"
year: 2022
bibkey: li2022unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.07160"}
  - {name: "Code", url: "https://github.com/microsoft/LAVENDER"}
tags: ['Applications', 'BERT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Unified vision45;language frameworks have greatly advanced in recent years most of which adopt an encoder45;decoder architecture to unify image45;text tasks as sequence45;to45;sequence generation. However existing video45;language (VidL) models still require task45;specific designs in model architecture and training objectives for each task. In this work we explore a unified VidL framework LAVENDER where Masked Language Modeling (MLM) is used as the common interface for all pre45;training and downstream tasks. Such unification leads to a simplified model architecture where only a lightweight MLM head instead of a decoder with much more parameters is needed on top of the multimodal encoder. Surprisingly experimental results show that this unified framework achieves competitive performance on 14 VidL benchmarks covering video question answering text45;to45;video retrieval and video captioning. Extensive analyses further demonstrate the advantage of LAVENDER over existing VidL methods in (i) supporting all downstream tasks with just a single set of parameter values when multi45;task finetuned; (ii) few45;shot generalization on various downstream tasks; and (iii) enabling zero45;shot evaluation on video question answering tasks. Code is available at https://github.com/microsoft/LAVENDER.
