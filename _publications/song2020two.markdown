---
layout: publication
title: Lightpaff A Two-stage Distillation Framework For Pre-training And Fine-tuning
authors: Song Kaitao, Sun Hao, Tan Xu, Qin Tao, Lu Jianfeng, Liu Hongzhi, Liu Tie-yan
conference: "Arxiv"
year: 2020
bibkey: song2020two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.12817"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While pre-training and fine-tuning e.g. BERT~(citepdevlin2018bert) GPT-2~(citepradford2019language) have achieved great success in language understanding and generation tasks the pre-trained models are usually too big for online deployment in terms of both memory cost and inference speed which hinders them from practical online usage. In this paper we propose LightPAFF a Lightweight Pre-training And Fine-tuning Framework that leverages two-stage knowledge distillation to transfer knowledge from a big teacher model to a lightweight student model in both pre-training and fine-tuning stages. In this way the lightweight model can achieve similar accuracy as the big teacher model but with much fewer parameters and thus faster online inference speed. LightPAFF can support different pre-training methods (such as BERT GPT-2 and MASS~(citepsong2019mass)) and be applied to many downstream tasks. Experiments on three language understanding tasks three language modeling tasks and three sequence to sequence generation tasks demonstrate that while achieving similar accuracy with the big BERT GPT-2 and MASS models LightPAFF reduces the model size by nearly 5x and improves online inference speed by 5x-7x.
