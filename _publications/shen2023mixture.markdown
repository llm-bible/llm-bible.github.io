---
layout: publication
title: Mixture45;of45;experts Meets Instruction Tuninga Winning Combination For Large Language Models
authors: Shen Sheng, Hou Le, Zhou Yanqi, Du Nan, Longpre Shayne, Wei Jason, Chung Hyung Won, Zoph Barret, Fedus William, Chen Xinyun, Vu Tu, Wu Yuexin, Chen Wuyang, Webson Albert, Li Yunxuan, Zhao Vincent, Yu Hongkun, Keutzer Kurt, Darrell Trevor, Zhou Denny
conference: "Arxiv"
year: 2023
bibkey: shen2023mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14705"}
tags: ['Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Sparse Mixture45;of45;Experts (MoE) is a neural architecture design that can be utilized to add learnable parameters to Large Language Models (LLMs) without increasing inference cost. Instruction tuning is a technique for training LLMs to follow instructions. We advocate combining these two approaches as we find that MoE models benefit more from instruction tuning than dense models. In particular we conduct empirical studies across three experimental setups (i) Direct finetuning on individual downstream tasks devoid of instruction tuning; (ii) Instructiontuning followed by in45;context few45;shot or zero45;shot generalization on downstream tasks; and (iii) Instruction tuning supplemented by further finetuning on individual downstream tasks. In the first scenario MoE models overall underperform dense models of identical computational capacity. This narrative however dramatically changes with the introduction of instruction tuning (second and third scenario) used independently or in conjunction with task45;specific finetuning. Our most powerful model FLAN45;MOE45;32B surpasses the performance of FLAN45;PALM45;62B on four benchmark tasks while using only a third of the FLOPs. The advancements embodied byFLAN45;MOE inspire a reevaluation of the design principles of large45;scale high45;performance language models in the framework of task45;agnostic learning.
