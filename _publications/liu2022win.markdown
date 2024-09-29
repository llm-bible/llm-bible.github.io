---
layout: publication
title: A Win45;win Deal Towards Sparse And Robust Pre45;trained Language Models
authors: Liu Yuanxin, Meng Fandong, Lin Zheng, Li Jiangnan, Fu Peng, Cao Yanan, Wang Weiping, Zhou Jie
conference: "Arxiv"
year: 2022
bibkey: liu2022win
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05211"}
  - {name: "Code", url: "https://github.com/llyx97/sparse&#45;and&#45;robust&#45;PLM"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Security', 'Training Techniques']
---
Despite the remarkable success of pre45;trained language models (PLMs) they still face two challenges First large45;scale PLMs are inefficient in terms of memory footprint and computation. Second on the downstream tasks PLMs tend to rely on the dataset bias and struggle to generalize to out45;of45;distribution (OOD) data. In response to the efficiency problem recent studies show that dense PLMs can be replaced with sparse subnetworks without hurting the performance. Such subnetworks can be found in three scenarios 1) the fine45;tuned PLMs 2) the raw PLMs and then fine45;tuned in isolation and even inside 3) PLMs without any parameter fine45;tuning. However these results are only obtained in the in45;distribution (ID) setting. In this paper we extend the study on PLMs subnetworks to the OOD setting investigating whether sparsity and robustness to dataset bias can be achieved simultaneously. To this end we conduct extensive experiments with the pre45;trained BERT model on three natural language understanding (NLU) tasks. Our results demonstrate that textbf123;sparse and robust subnetworks (SRNets) can consistently be found in BERT125; across the aforementioned three scenarios using different training and compression methods. Furthermore we explore the upper bound of SRNets using the OOD information and show that textbf123;there exist sparse and almost unbiased BERT subnetworks125;. Finally we present 1) an analytical study that provides insights on how to promote the efficiency of SRNets searching process and 2) a solution to improve subnetworks performance at high sparsity. The code is available at https://github.com/llyx97/sparse&#45;and&#45;robust&#45;PLM.
