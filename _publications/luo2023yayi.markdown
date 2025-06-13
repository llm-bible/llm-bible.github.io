---
layout: publication
title: 'YAYI 2: Multilingual Open-source Large Language Models'
authors: Yin Luo, Qingchao Kong, Nan Xu, Jia Cao, Bao Hao, Baoyu Qu, Bo Chen, Chao Zhu, Chenyang Zhao, Donglei Zhang, Fan Feng, Feifei Zhao, Hailong Sun, Hanxuan Yang, Haojun Pan, Hongyu Liu, Jianbin Guo, Jiangtao Du, Jingyi Wang, Junfeng Li, Lei Sun, Liduo Liu, Lifeng Dong, Lili Liu, Lin Wang, Liwen Zhang, Minzheng Wang, Pin Wang, Ping Yu, Qingxiao Li, Rui Yan, Rui Zou, Ruiqun Li, Taiwen Huang, Xiaodong Wang, Xiaofei Wu, Xin Peng, Xina Zhang, Xing Fang, Xinglin Xiao, Yanni Hao, Yao Dong, Yigang Wang, Ying Liu, Yongyu Jiang, Yungan Wang, Yuqi Wang, Zhangsheng Wang, Zhaoxin Yu, Zhen Luo, Wenji Mao, Lei Wang, Dajun Zeng
conference: "Arxiv"
year: 2023
bibkey: luo2023yayi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14862"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
As the latest advancements in natural language processing, large language
models (LLMs) have achieved human-level language understanding and generation
abilities in many real-world tasks, and even have been regarded as a potential
path to the artificial general intelligence. To better facilitate research on
LLMs, many open-source LLMs, such as Llama 2 and Falcon, have recently been
proposed and gained comparable performances to proprietary models. However,
these models are primarily designed for English scenarios and exhibit poor
performances in Chinese contexts. In this technical report, we propose YAYI 2,
including both base and chat models, with 30 billion parameters. YAYI 2 is
pre-trained from scratch on a multilingual corpus which contains 2.65 trillion
tokens filtered by our pre-training data processing pipeline. The base model is
aligned with human values through supervised fine-tuning with millions of
instructions and reinforcement learning from human feedback. Extensive
experiments on multiple benchmarks, such as MMLU and CMMLU, consistently
demonstrate that the proposed YAYI 2 outperforms other similar sized
open-source models.
