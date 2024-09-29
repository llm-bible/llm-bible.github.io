---
layout: publication
title: 'Composing Parameter-efficient Modules With Arithmetic Operations'
authors: Zhang Jinghan, Chen Shiqi, Liu Junteng, He Junxian
conference: "Arxiv"
year: 2023
bibkey: zhang2023composing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.14870"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
As an efficient alternative to conventional full finetuning parameter-efficient finetuning (PEFT) is becoming the prevailing method to adapt pretrained language models. In PEFT a lightweight module is learned on each dataset while the underlying pretrained language model remains unchanged resulting in multiple compact modules representing diverse skills when applied to various domains and tasks. In this paper we propose to compose these parameter-efficient modules through linear arithmetic operations in the weight space thereby integrating different module capabilities. Specifically we first define addition and negation operators for the module and then further compose these two basic operators to perform flexible arithmetic. Our approach requires (emphno additional training) and enables highly flexible module composition. We apply different arithmetic operations to compose the parameter-efficient modules for (1) distribution generalization (2) multi-tasking (3) unlearning and (4) domain transfer. Additionally we extend our approach to detoxify Alpaca-LoRA the latest instruction-tuned large language model based on LLaMA. Empirical results demonstrate that our approach produces new and effective parameter-efficient modules that significantly outperform existing ones across all settings.
