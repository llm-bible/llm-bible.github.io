---
layout: publication
title: Llava45;mole Sparse Mixture Of Lora Experts For Mitigating Data Conflicts In Instruction Finetuning Mllms
authors: Chen Shaoxiang, Jie Zequn, Ma Lin
conference: "Arxiv"
year: 2024
bibkey: chen2024llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16160"}
tags: ['Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Instruction finetuning on a variety of image45;text instruction data is the key to obtaining a versatile Multimodal Large Language Model (MLLM) and different configurations of the instruction data can lead to finetuned models with different capabilities. However we have discovered that data conflicts are inevitable when mixing instruction data from distinct domains which can result in performance drops for tasks of a specific domain. To address this issue we propose to apply an efficient Mixture of Experts (MoE) design which is a sparse Mixture of LoRA Experts (MoLE) for instruction finetuning MLLMs. Within the Transformer layers we extend the popular Low45;Rank Adaption (LoRA) method by creating a set of LoRA experts specifically for the MLP layer and route each token to the top45;1 expert based on a routing function allowing adaptive choices for tokens from different domains. Since the LoRA experts are sparsely activated the training and inference cost are kept roughly constant compared to the original LoRA method. By replacing the plain45;LoRA of LLaVA45;1.5 with our MoE design our final model is named LLaVA45;MoLE. Extensive experiments proved that LLaVA45;MoLE effectively mitigates the data conflict issue when mixing multiple distinct instruction datasets with various configurations and achieves consistent performance gains over the strong plain45;LoRA baselines. Most importantly on the mixed datasets LLaVA45;MoLE can even outperform the plain45;LoRA baseline trained with twice the samples.
