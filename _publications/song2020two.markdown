---
layout: publication
title: Lightpaff A Two45;stage Distillation Framework For Pre45;training And Fine45;tuning
authors: Song Kaitao, Sun Hao, Tan Xu, Qin Tao, Lu Jianfeng, Liu Hongzhi, Liu Tie-yan
conference: "Arxiv"
year: 2020
bibkey: song2020two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.12817"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While pre45;training and fine45;tuning e.g. BERT~citep123;devlin2018bert125; GPT45;2~citep123;radford2019language125; have achieved great success in language understanding and generation tasks the pre45;trained models are usually too big for online deployment in terms of both memory cost and inference speed which hinders them from practical online usage. In this paper we propose LightPAFF a Lightweight Pre45;training And Fine45;tuning Framework that leverages two45;stage knowledge distillation to transfer knowledge from a big teacher model to a lightweight student model in both pre45;training and fine45;tuning stages. In this way the lightweight model can achieve similar accuracy as the big teacher model but with much fewer parameters and thus faster online inference speed. LightPAFF can support different pre45;training methods (such as BERT GPT45;2 and MASS~citep123;song2019mass125;) and be applied to many downstream tasks. Experiments on three language understanding tasks three language modeling tasks and three sequence to sequence generation tasks demonstrate that while achieving similar accuracy with the big BERT GPT45;2 and MASS models LightPAFF reduces the model size by nearly 5x and improves online inference speed by 5x45;7x.
