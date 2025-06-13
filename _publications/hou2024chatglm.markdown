---
layout: publication
title: 'Chatglm-rlhf: Practices Of Aligning Large Language Models With Human Feedback'
authors: Zhenyu Hou, Yilin Niu, Zhengxiao Du, Xiaohan Zhang, Xiao Liu, Aohan Zeng, Qinkai Zheng, Minlie Huang, Hongning Wang, Jie Tang, Yuxiao Dong
conference: "Arxiv"
year: 2024
bibkey: hou2024chatglm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00934"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques']
---
ChatGLM is a free-to-use AI service powered by the ChatGLM family of large
language models (LLMs). In this paper, we present the ChatGLM-RLHF pipeline --
a reinforcement learning from human feedback (RLHF) system -- designed to
enhance ChatGLM's alignment with human preferences. ChatGLM-RLHF encompasses
three major components: the collection of human preference data, the training
of the reward model, and the optimization of policies. Throughout the process
of integrating ChatGLM-RLHF into production, we encountered and addressed
several unprecedented challenges. We introduce the strategies to mitigate
reward variance for stabilized large-scale training, implement model
parallelism with fused gradient-descent, and design regularization constraints
to avoid catastrophic forgetting in LLMs. Experiments show that ChatGLM-RLHF
brings significant improvements in alignment tasks compared to the supervised
fine-tuned (SFT) version of ChatGLM. For instance, it achieves on average 15%
more wins against ChatGLM-SFT in Chinese alignment tasks. The work presents our
practices of aligning LLMs with human preferences, offering insights into the
challenges and solutions in RLHF implementations.
