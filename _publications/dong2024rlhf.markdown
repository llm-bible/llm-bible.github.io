---
layout: publication
title: RLHF Workflow From Reward Modeling To Online RLHF
authors: Dong Hanze, Xiong Wei, Pang Bo, Wang Haoxiang, Zhao Han, Zhou Yingbo, Jiang Nan, Sahoo Doyen, Xiong Caiming, Zhang Tong
conference: "Arxiv"
year: 2024
bibkey: dong2024rlhf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07863"}
  - {name: "Code", url: "https://github.com/RLHFlow/RLHF&#45;Reward&#45;Modeling"}
  - {name: "Code", url: "https://github.com/RLHFlow/Online&#45;RLHF"}
tags: ['Agentic', 'Fine Tuning', 'Has Code', 'Reinforcement Learning', 'Tools']
---
We present the workflow of Online Iterative Reinforcement Learning from Human Feedback (RLHF) in this technical report which is widely reported to outperform its offline counterpart by a large margin in the recent large language model (LLM) literature. However existing open45;source RLHF projects are still largely confined to the offline learning setting. In this technical report we aim to fill in this gap and provide a detailed recipe that is easy to reproduce for online iterative RLHF. In particular since online human feedback is usually infeasible for open45;source communities with limited resources we start by constructing preference models using a diverse set of open45;source datasets and use the constructed proxy preference model to approximate human feedback. Then we discuss the theoretical insights and algorithmic principles behind online iterative RLHF followed by a detailed practical implementation. Our trained LLM LLaMA45;345;8B45;SFR45;Iterative45;DPO45;R achieves impressive performance on LLM chatbot benchmarks including AlpacaEval45;2 Arena45;Hard and MT45;Bench as well as other academic benchmarks such as HumanEval and TruthfulQA. We have shown that supervised fine45;tuning (SFT) and iterative RLHF can obtain state45;of45;the45;art performance with fully open45;source datasets. Further we have made our models curated datasets and comprehensive step45;by45;step code guidebooks publicly available. Please refer to https://github.com/RLHFlow/RLHF&#45;Reward&#45;Modeling and https://github.com/RLHFlow/Online&#45;RLHF for more detailed information.
