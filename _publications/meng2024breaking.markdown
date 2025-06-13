---
layout: publication
title: 'Periodiclora: Breaking The Low-rank Bottleneck In Lora Optimization'
authors: Xiangdi Meng, Damai Dai, Weiyao Luo, Zhe Yang, Shaoxiang Wu, Xiaochen Wang, Peiyi Wang, Qingxiu Dong, Liang Chen, Zhifang Sui
conference: "Arxiv"
year: 2024
bibkey: meng2024breaking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.16141'}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods']
---
Supervised fine-tuning is the most common method to adapt large language
models (LLMs) to downstream tasks, but full fine-tuning LLMs requires massive
computational resources. Recently, parameter-efficient fine-tuning (PEFT)
methods have been widely studied due to its cost-effectiveness. LoRA is one of
the most widely used methods, which assumes that the optimization process is
essentially low-dimensional. Although LoRA fine-tuning is effective, there is
still a performance gap compared to full fine-tuning, since its weight update
is limited to low-rank matrices. In order to break the low-rank bottleneck in
LoRA Optimization, we propose PeriodicLoRA (PLoRA), which accumulates low-rank
update matrices multiple times to achieve a higher update rank. PLoRA has
multiple training stages. During each stage, we still update only the LoRA
weights. However, at the end of each stage, we unload the LoRA weights into the
backbone parameters and then reinitialize the LoRA states. Experimental results
show that PLoRA has stronger learning ability, approximately 1.8 times that of
LoRA's learning ability at most, but it does not increase memory usage.
Further, we introduce a momentum-based unloading strategy for PLoRA to mitigate
the training instability.
