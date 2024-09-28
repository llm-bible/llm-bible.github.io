---
layout: publication
title: Tiny Refinements Elicit Resilience Toward Efficient Prefix-Model Against LLM Red-Teaming
authors: Liu Jiaxu, Yin Xiangyu, Wu Sihao, Wang Jianhong, Fang Meng, Yi Xinping, Huang Xiaowei
conference: "Arxiv"
year: 2024
bibkey: liu2024tiny
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12604"}
tags: ['ARXIV', 'Agentic', 'Applications', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools']
---
With the proliferation of red-teaming strategies for Large Language Models (LLMs) the deficiency in the literature about improving the safety and robustness of LLM defense strategies is becoming increasingly pronounced. This paper introduces the LLM-based model as a plug-and-play prefix module designed to reconstruct the input prompt with just a few (<30) additional tokens effectively reducing toxicity in responses from target LLMs. The sentinel model naturally overcomes the and for fine-tuning large target models. We employ an interleaved training regimen using Proximal Policy Optimization (PPO) to optimize both red team and sentinel models dynamically incorporating a value head-sharing mechanism inspired by the multi-agent centralized critic to manage the complex interplay between agents. Our extensive experiments across text-to-text and text-to-image demonstrate the effectiveness of our approach in mitigating toxic outputs even when dealing with larger models like and highlighting the potential of our framework in enhancing safety and robustness in various applications.
