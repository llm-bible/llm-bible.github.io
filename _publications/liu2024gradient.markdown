---
layout: publication
title: 'GRIN: Gradient-informed Moe'
authors: Liyuan Liu, Young Jin Kim, Shuohang Wang, Chen Liang, Yelong Shen, Hao Cheng, Xiaodong Liu, Masahiro Tanaka, Xiaoxia Wu, Wenxiang Hu, Vishrav Chaudhary, Zeqi Lin, Chenruidong Zhang, Jilong Xue, Hany Awadalla, Jianfeng Gao, Weizhu Chen
conference: "Arxiv"
year: 2024
bibkey: liu2024gradient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.12136'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'GPT', 'Training Techniques', 'Pretraining Methods']
---
Mixture-of-Experts (MoE) models scale more effectively than dense models due
to sparse computation through expert routing, selectively activating only a
small subset of expert modules. However, sparse computation challenges
traditional training practices, as discrete expert routing hinders standard
backpropagation and thus gradient-based optimization, which are the cornerstone
of deep learning. To better pursue the scaling power of MoE, we introduce GRIN
(GRadient-INformed MoE training), which incorporates sparse gradient estimation
for expert routing and configures model parallelism to avoid token dropping.
Applying GRIN to autoregressive language modeling, we develop a top-2
16\\(\times\\)3.8B MoE model. Our model, with only 6.6B activated parameters,
outperforms a 7B dense model and matches the performance of a 14B dense model
trained on the same data. Extensive evaluations across diverse tasks
demonstrate the potential of GRIN to significantly enhance MoE efficacy,
achieving 79.4 on MMLU, 83.7 on HellaSwag, 74.4 on HumanEval, and 58.9 on MATH.
