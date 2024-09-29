---
layout: publication
title: Chatglm45;rlhf Practices Of Aligning Large Language Models With Human Feedback
authors: Hou Zhenyu, Niu Yilin, Du Zhengxiao, Zhang Xiaohan, Liu Xiao, Zeng Aohan, Zheng Qinkai, Huang Minlie, Wang Hongning, Tang Jie, Dong Yuxiao
conference: "Arxiv"
year: 2024
bibkey: hou2024chatglm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00934"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
ChatGLM is a free45;to45;use AI service powered by the ChatGLM family of large language models (LLMs). In this paper we present the ChatGLM45;RLHF pipeline 45;45; a reinforcement learning from human feedback (RLHF) system 45;45; designed to enhance ChatGLMs alignment with human preferences. ChatGLM45;RLHF encompasses three major components the collection of human preference data the training of the reward model and the optimization of policies. Throughout the process of integrating ChatGLM45;RLHF into production we encountered and addressed several unprecedented challenges. We introduce the strategies to mitigate reward variance for stabilized large45;scale training implement model parallelism with fused gradient45;descent and design regularization constraints to avoid catastrophic forgetting in LLMs. Experiments show that ChatGLM45;RLHF brings significant improvements in alignment tasks compared to the supervised fine45;tuned (SFT) version of ChatGLM. For instance it achieves on average 1537; more wins against ChatGLM45;SFT in Chinese alignment tasks. The work presents our practices of aligning LLMs with human preferences offering insights into the challenges and solutions in RLHF implementations.
