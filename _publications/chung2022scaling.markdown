---
layout: publication
title: 'Scaling Instruction-finetuned Language Models'
authors: Chung Hyung Won, Hou Le, Longpre Shayne, Zoph Barret, Tay Yi, Fedus William, Li Yunxuan, Wang Xuezhi, Dehghani Mostafa, Brahma Siddhartha, Webson Albert, Gu Shixiang Shane, Dai Zhuyun, Suzgun Mirac, Chen Xinyun, Chowdhery Aakanksha, Castro-ros Alex, Pellat Marie, Robinson Kevin, Valter Dasha, Narang Sharan, Mishra Gaurav, Yu Adams, Zhao Vincent, Huang Yanping, Dai Andrew, Yu Hongkun, Petrov Slav, Chi Ed H., Dean Jeff, Devlin Jacob, Roberts Adam, Zhou Denny, Le Quoc V., Wei Jason
conference: "Arxiv"
year: 2022
bibkey: chung2022scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.11416"}
tags: ['Few Shot', 'Pretraining Methods', 'Prompting', 'RAG']
---
'Finetuning language models on a collection of datasets phrased as instructions has been shown to improve model performance and generalization to unseen tasks. In this paper we explore instruction finetuning with a particular focus on (1) scaling the number of tasks, (2) scaling the model size, and (3) finetuning on chain-of-thought data. We find that instruction finetuning with the above aspects dramatically improves performance on a variety of model classes (PaLM, T5, U-PaLM), prompting setups (zero-shot, few-shot, CoT), and evaluation benchmarks (MMLU, BBH, TyDiQA, MGSM, open-ended generation). For instance, Flan-PaLM 540B instruction-finetuned on 1.8K tasks outperforms PALM 540B by a large margin (+9.4&#37; on average). Flan-PaLM 540B achieves state-of-the-art performance on several benchmarks, such as 75.2&#37; on five-shot MMLU. We also publicly release Flan-T5 checkpoints, which achieve strong few-shot performance even compared to much larger models, such as PaLM 62B. Overall, instruction finetuning is a general method for improving the performance and usability of pretrained language models.'
