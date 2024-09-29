---
layout: publication
title: ELLE Efficient Lifelong Pre-training For Emerging Data
authors: Qin Yujia, Zhang Jiajie, Lin Yankai, Liu Zhiyuan, Li Peng, Sun Maosong, Zhou Jie
conference: "Arxiv"
year: 2022
bibkey: qin2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.06311"}
  - {name: "Code", url: "https://github.com/thunlp/ELLE"}
tags: ['BERT', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Current pre-trained language models (PLM) are typically trained with static data ignoring that in real-world scenarios streaming data of various sources may continuously grow. This requires PLMs to integrate the information from all the sources in a lifelong manner. Although this goal could be achieved by exhaustive pre-training on all the existing data such a process is known to be computationally expensive. To this end we propose ELLE aiming at efficient lifelong pre-training for emerging data. Specifically ELLE consists of (1) function preserved model expansion which flexibly expands an existing PLMs width and depth to improve the efficiency of knowledge acquisition; and (2) pre-trained domain prompts which disentangle the versatile knowledge learned during pre-training and stimulate the proper knowledge for downstream tasks. We experiment ELLE with streaming data from 5 domains on BERT and GPT. The results show the superiority of ELLE over various lifelong learning baselines in both pre-training efficiency and downstream performances. The codes are publicly available at https://github.com/thunlp/ELLE."
