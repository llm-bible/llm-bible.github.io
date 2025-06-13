---
layout: publication
title: 'Elder: Getting Efficient Llms Through Data-driven Regularized Layer-wise Pruning'
authors: Mingkuan Feng, Jinyang Wu, Siyuan Liu, Shuai Zhang, Hongjian Fang, Ruihan Jin, Feihu Che, Pengpeng Shao, Zhengqi Wen, Jianhua Tao
conference: "Arxiv"
year: 2025
bibkey: feng2025getting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18232'}
tags: ['Language Modeling', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pruning', 'Pretraining Methods']
---
The deployment of Large language models (LLMs) in many fields is largely hindered by their high computational and memory costs. Recent studies suggest that LLMs exhibit sparsity, which can be used for pruning. Previous pruning methods typically follow a prune-then-finetune paradigm. Since the pruned parts still contain valuable information, statically removing them without updating the remaining parameters often results in irreversible performance degradation, requiring costly recovery fine-tuning (RFT) to maintain performance. To address this, we propose a novel paradigm: first apply regularization, then prune. Based on this paradigm, we propose ELDeR: Getting Efficient LLMs through Data-Driven Regularized Layer-wise Pruning. We multiply the output of each transformer layer by an initial weight, then we iteratively learn the weights of each transformer layer by using a small amount of data in a simple way. After that, we apply regularization to the difference between the output and input of the layers with smaller weights, forcing the information to be transferred to the remaining layers. Compared with direct pruning, ELDeR reduces the information loss caused by direct parameter removal, thus better preserving the model's language modeling ability. Experimental results show that ELDeR achieves superior performance compared with powerful layer-wise structured pruning methods, while greatly reducing RFT computational costs. Since ELDeR is a layer-wise pruning method, its end-to-end acceleration effect is obvious, making it a promising technique for efficient LLMs.
