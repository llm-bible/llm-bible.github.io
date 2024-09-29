---
layout: publication
title: A Win-win Deal Towards Sparse and Robust Pre-trained Language Models
authors: Liu Yuanxin, Meng Fandong, Lin Zheng, Li Jiangnan, Fu Peng, Cao Yanan, Wang Weiping, Zhou Jie
conference: "Arxiv"
year: 2022
bibkey: liu2022win
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05211"}
  - {name: "Code", url: "https://github.com/llyx97/sparse-and-robust-PLM"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques']
---
Despite the remarkable success of pre-trained language models (PLMs) they still face two challenges First large-scale PLMs are inefficient in terms of memory footprint and computation. Second on the downstream tasks PLMs tend to rely on the dataset bias and struggle to generalize to out-of-distribution (OOD) data. In response to the efficiency problem recent studies show that dense PLMs can be replaced with sparse subnetworks without hurting the performance. Such subnetworks can be found in three scenarios 1) the fine-tuned PLMs 2) the raw PLMs and then fine-tuned in isolation and even inside 3) PLMs without any parameter fine-tuning. However these results are only obtained in the in-distribution (ID) setting. In this paper we extend the study on PLMs subnetworks to the OOD setting investigating whether sparsity and robustness to dataset bias can be achieved simultaneously. To this end we conduct extensive experiments with the pre-trained BERT model on three natural language understanding (NLU) tasks. Our results demonstrate that textbfsparse and robust subnetworks (SRNets) can consistently be found in BERT across the aforementioned three scenarios using different training and compression methods. Furthermore we explore the upper bound of SRNets using the OOD information and show that textbfthere exist sparse and almost unbiased BERT subnetworks. Finally we present 1) an analytical study that provides insights on how to promote the efficiency of SRNets searching process and 2) a solution to improve subnetworks performance at high sparsity. The code is available at https://github.com/llyx97/sparse-and-robust-PLM.
