---
layout: publication
title: 'DAPO: An Open-source LLM Reinforcement Learning System At Scale'
authors: Qiying Yu, Zheng Zhang, Ruofei Zhu, Yufeng Yuan, Xiaochen Zuo, Yu Yue, Weinan Dai, Tiantian Fan, Gaohong Liu, Lingjun Liu, Xin Liu, Haibin Lin, Zhiqi Lin, Bole Ma, Guangming Sheng, Yuxuan Tong, Chi Zhang, Mofan Zhang, Wang Zhang, Hang Zhu, Jinhua Zhu, Jiaze Chen, Jiangjie Chen, Chengyi Wang, Hongli Yu, Yuxuan Song, Xiangpeng Wei, Hao Zhou, Jingjing Liu, Wei-ying Ma, Ya-qin Zhang, Lin Yan, Mu Qiao, Yonghui Wu, Mingxuan Wang
conference: "Arxiv"
year: 2025
bibkey: yu2025open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14476"}
tags: ['Training Techniques', 'Agentic', 'Tools', 'Reinforcement Learning']
---
Inference scaling empowers LLMs with unprecedented reasoning ability, with reinforcement learning as the core technique to elicit complex reasoning. However, key technical details of state-of-the-art reasoning LLMs are concealed (such as in OpenAI o1 blog and DeepSeek R1 technical report), thus the community still struggles to reproduce their RL training results. We propose the \\(\textbf\{D\}\\)ecoupled Clip and \\(\textbf\{D\}\\)ynamic s\\(\textbf\{A\}\\)mpling \\(\textbf\{P\}\\)olicy \\(\textbf\{O\}\\)ptimization (\\(\textbf\{DAPO\}\\)) algorithm, and fully open-source a state-of-the-art large-scale RL system that achieves 50 points on AIME 2024 using Qwen2.5-32B base model. Unlike previous works that withhold training details, we introduce four key techniques of our algorithm that make large-scale LLM RL a success. In addition, we open-source our training code, which is built on the verl framework, along with a carefully curated and processed dataset. These components of our open-source system enhance reproducibility and support future research in large-scale LLM RL.
