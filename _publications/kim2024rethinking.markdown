---
layout: publication
title: Rethinking The Role Of Proxy Rewards In Language Model Alignment
authors: Kim Sungdong, Seo Minjoon
conference: "Arxiv"
year: 2024
bibkey: kim2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03469"}
  - {name: "Code", url: "https://github.com/naver&#45;ai/rethinking&#45;proxy&#45;reward"}
tags: ['Agentic', 'Has Code', 'Reinforcement Learning', 'Training Techniques']
---
Learning from human feedback via proxy reward modeling has been studied to align Large Language Models (LLMs) with human values. However achieving reliable training through that proxy reward model (RM) is not a trivial problem and its behavior remained as a black45;box. In this paper we study the role of proxy rewards in the LLM alignment via reverse reward engineering by composing interpretable features as a white45;box reward function. We aim to replicate the ground truth (gold) reward signal by achieving a monotonic relationship between the proxy and gold reward signals after training the model using the proxy reward in reinforcement learning (RL). Our findings indicate that successfully emulating the gold reward requires generating responses that are relevant with enough length to open45;ended questions while also ensuring response consistency in closed45;ended questions. Furthermore resulting models optimizing our devised white45;box reward show competitive performances with strong open45;source RMs in alignment benchmarks. We highlight its potential usage as a simple but strong reward baseline for the LLM alignment not requiring explicit human feedback dataset and RM training. Our code is available at https://github.com/naver&#45;ai/rethinking&#45;proxy&#45;reward.
