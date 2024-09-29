---
layout: publication
title: Scaling Instruction45;finetuned Language Models
authors: Hyung Won Chung, Le Hou, Shayne Longpre, Barret Zoph, Yi Tay, William Fedus, Yunxuan Li, Xuezhi Wang, Mostafa Dehghani, Siddhartha Brahma, Albert Webson, Shixiang Shane Gu, Zhuyun Dai, Mirac Suzgun, Xinyun Chen, Aakanksha Chowdhery, Alex Castro-ros, Marie Pellat, Kevin Robinson, Dasha Valter, Sharan Narang, Gaurav Mishra, Adams Yu, Vincent Zhao, Yanping Huang, Andrew Dai, Hongkun Yu, Slav Petrov, Ed H. Chi, Jeff Dean, Jacob Devlin, Adam Roberts, Denny Zhou, Quoc V. Le, Jason Wei
conference: "Arxiv"
year: 2022
bibkey: won2022scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.11416v5"}
tags: ['Pretraining Methods', 'Prompting', 'RAG']
---
Finetuning language models on a collection of datasets phrased as instructions has been shown to improve model performance and generalization to unseen tasks. In this paper we explore instruction finetuning with a particular focus on (1) scaling the number of tasks (2) scaling the model size and (3) finetuning on chain45;of45;thought data. We find that instruction finetuning with the above aspects dramatically improves performance on a variety of model classes (PaLM T5 U45;PaLM) prompting setups (zero45;shot few45;shot CoT) and evaluation benchmarks (MMLU BBH TyDiQA MGSM open45;ended generation). For instance Flan45;PaLM 540B instruction45;finetuned on 1.8K tasks outperforms PALM 540B by a large margin (+9.437; on average). Flan45;PaLM 540B achieves state45;of45;the45;art performance on several benchmarks such as 75.237; on five45;shot MMLU. We also publicly release Flan45;T5 checkpoints which achieve strong few45;shot performance even compared to much larger models such as PaLM 62B. Overall instruction finetuning is a general method for improving the performance and usability of pretrained language models.
