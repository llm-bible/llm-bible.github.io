---
layout: publication
title: List Lite Prompted Self45;training Makes Parameter45;efficient Few45;shot Learners
authors: Wang Yaqing, Mukherjee Subhabrata, Liu Xiaodong, Gao Jing, Awadallah Ahmed Hassan, Gao Jianfeng
conference: "Arxiv"
year: 2021
bibkey: wang2021lite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.06274"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Survey Paper', 'Training Techniques']
---
We present a new method LiST is short for Lite Prompted Self45;Training for parameter45;efficient fine45;tuning of large pre45;trained language models (PLMs) for few45;shot learning. LiST improves over recent methods that adopt prompt45;based fine45;tuning (FN) using two key techniques. The first is the use of self45;training to leverage large amounts of unlabeled data for prompt45;based FN in few45;shot settings. We use self45;training in conjunction with meta45;learning for re45;weighting noisy pseudo45;prompt labels. Self45;training is expensive as it requires updating all the model parameters repetitively. Therefore we use a second technique for light45;weight fine45;tuning where we introduce a small number of task45;specific parameters that are fine45;tuned during self45;training while keeping the PLM encoder frozen. Our experiments show that LiST can effectively leverage unlabeled data to improve the model performance for few45;shot learning. Additionally the fine45;tuning is efficient as it only updates a small percentage of parameters and the overall model footprint is reduced since several tasks can share a common PLM encoder as backbone. A comprehensive study on six NLU tasks demonstrate LiST to improve by 3537; over classic fine45;tuning and 637; over prompt45;based FN with 9637; reduction in number of trainable parameters when fine45;tuned with no more than 30 labeled examples from each task. With only 14M tunable parameters LiST outperforms GPT45;3 in45;context learning by 3337; on few45;shot NLU tasks.
