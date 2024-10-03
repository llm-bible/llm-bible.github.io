---
layout: publication
title: 'List: Lite Prompted Self-training Makes Parameter-efficient Few-shot Learners'
authors: Wang Yaqing, Mukherjee Subhabrata, Liu Xiaodong, Gao Jing, Awadallah Ahmed Hassan, Gao Jianfeng
conference: "Arxiv"
year: 2021
bibkey: wang2021lite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.06274"}
tags: ['Few Shot', 'Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Survey Paper', 'Training Techniques']
---
We present a new method LiST is short for Lite Prompted Self-Training for parameter-efficient fine-tuning of large pre-trained language models (PLMs) for few-shot learning. LiST improves over recent methods that adopt prompt-based fine-tuning (FN) using two key techniques. The first is the use of self-training to leverage large amounts of unlabeled data for prompt-based FN in few-shot settings. We use self-training in conjunction with meta-learning for re-weighting noisy pseudo-prompt labels. Self-training is expensive as it requires updating all the model parameters repetitively. Therefore, we use a second technique for light-weight fine-tuning where we introduce a small number of task-specific parameters that are fine-tuned during self-training while keeping the PLM encoder frozen. Our experiments show that LiST can effectively leverage unlabeled data to improve the model performance for few-shot learning. Additionally, the fine-tuning is efficient as it only updates a small percentage of parameters and the overall model footprint is reduced since several tasks can share a common PLM encoder as backbone. A comprehensive study on six NLU tasks demonstrate LiST to improve by 35&#37; over classic fine-tuning and 6&#37; over prompt-based FN with 96&#37; reduction in number of trainable parameters when fine-tuned with no more than 30 labeled examples from each task. With only 14M tunable parameters, LiST outperforms GPT-3 in-context learning by 33&#37; on few-shot NLU tasks.
