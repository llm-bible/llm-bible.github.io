---
layout: publication
title: CPM45;2 Large45;scale Cost45;effective Pre45;trained Language Models
authors: Zhengyan Zhang, Yuxian Gu, Xu Han, Shengqi Chen, Chaojun Xiao, Zhenbo Sun, Yuan Yao, Fanchao Qi, Jian Guan, Pei Ke, Yanzheng Cai, Guoyang Zeng, Zhixing Tan, Zhiyuan Liu, Minlie Huang, Wentao Han, Yang Liu, Xiaoyan Zhu, Maosong Sun
conference: "Arxiv"
year: 2021
bibkey: zhang2021cpm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2106.10715v3"}
  - {name: "Code", url: "https://github.com/TsinghuaAI/CPM"}
tags: ['Efficiency And Optimization', 'Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
In recent years the size of pre45;trained language models (PLMs) has grown by leaps and bounds. However efficiency issues of these large45;scale PLMs limit their utilization in real45;world scenarios. We present a suite of cost45;effective techniques for the use of PLMs to deal with the efficiency issues of pre45;training fine45;tuning and inference. (1) We introduce knowledge inheritance to accelerate the pre45;training process by exploiting existing PLMs instead of training models from scratch. (2) We explore the best practice of prompt tuning with large45;scale PLMs. Compared with conventional fine45;tuning prompt tuning significantly reduces the number of task45;specific parameters. (3) We implement a new inference toolkit namely InfMoE for using large45;scale PLMs with limited computational resources. Based on our cost45;effective pipeline we pre45;train two models an encoder45;decoder bilingual model with 11 billion parameters (CPM45;2) and its corresponding MoE version with 198 billion parameters. In our experiments we compare CPM45;2 with mT5 on downstream tasks. Experimental results show that CPM45;2 has excellent general language intelligence. Moreover we validate the efficiency of InfMoE when conducting inference of large45;scale models having tens of billions of parameters on a single GPU. All source code and model parameters are available at https://github.com/TsinghuaAI/CPM.
