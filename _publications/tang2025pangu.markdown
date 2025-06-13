---
layout: publication
title: 'Pangu Ultra Moe: How To Train Your Big Moe On Ascend Npus'
authors: Yehui Tang, Yichun Yin, Yaoyuan Wang, Hang Zhou, Yu Pan, Wei Guo, Ziyang Zhang, Miao Rang, Fangcheng Liu, Naifu Zhang, Binghan Li, Yonghan Dong, Xiaojun Meng, Yasheng Wang, Dong Li, Yin Li, Dandan Tu, Can Chen, Youliang Yan, Fisher Yu, Ruiming Tang, Yunhe Wang, Botian Huang, Bo Wang, Boxiao Liu, Changzheng Zhang, Da Kuang, Fei Liu, Gang Huang, Jiansheng Wei, Jiarui Qin, Jie Ran, Jinpeng Li, Jun Zhao, Liang Dai, Lin Li, Liqun Deng, Peifeng Qin, Pengyuan Zeng, Qiang Gu, Shaohua Tang, Shengjun Cheng, Tao Gao, Tao Yu, Tianshu Li, Tianyu Bi, Wei He, Weikai Mao, Wenyong Huang, Wulong Liu, Xiabing Li, Xianzhi Yu, Xueyu Wu, Xu He, Yangkai Du, Yan Xu, Ye Tian, Yimeng Wu, Yongbing Huang, Yong Tian, Yong Zhu, Yue Li, Yufei Wang, Yuhang Gai, Yujun Li, Yu Luo, Yunsheng Ni, Yusen Sun, Zelin Chen, Zhe Liu, Zhicheng Liu, Zhipeng Tu, Zilin Ding, Zongyuan Zhan
conference: "Arxiv"
year: 2025
bibkey: tang2025pangu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04519"}
tags: ['Training Techniques', 'RAG', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Sparse large language models (LLMs) with Mixture of Experts (MoE) and close
to a trillion parameters are dominating the realm of most capable language
models. However, the massive model scale poses significant challenges for the
underlying software and hardware systems. In this paper, we aim to uncover a
recipe to harness such scale on Ascend NPUs. The key goals are better usage of
the computing resources under the dynamic sparse model structures and
materializing the expected performance gain on the actual hardware. To select
model configurations suitable for Ascend NPUs without repeatedly running the
expensive experiments, we leverage simulation to compare the trade-off of
various model hyperparameters. This study led to Pangu Ultra MoE, a sparse LLM
with 718 billion parameters, and we conducted experiments on the model to
verify the simulation results. On the system side, we dig into Expert
Parallelism to optimize the communication between NPU devices to reduce the
synchronization overhead. We also optimize the memory efficiency within the
devices to further reduce the parameter and activation management overhead. In
the end, we achieve an MFU of 30.0% when training Pangu Ultra MoE, with
performance comparable to that of DeepSeek R1, on 6K Ascend NPUs, and
demonstrate that the Ascend system is capable of harnessing all the training
stages of the state-of-the-art language models. Extensive experiments indicate
that our recipe can lead to efficient training of large-scale sparse language
models with MoE. We also study the behaviors of such models for future
reference.
