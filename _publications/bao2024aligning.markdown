---
layout: publication
title: 'Aligning Large Language Models From Self-reference AI Feedback With One General Principle'
authors: Bao Rong, Zheng Rui, Dou Shihan, Wang Xiao, Zhou Enyu, Wang Bo, Zhang Qi, Ding Liang, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: bao2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11190"}
tags: ['Agentic', 'Ethics And Bias', 'Reinforcement Learning', 'Tools']
---
In aligning large language models (LLMs) utilizing feedback from existing advanced AI rather than humans is an important method to scale supervisory signals. However it is highly challenging for AI to understand human intentions and societal values and provide accurate preference feedback based on these. Current AI feedback methods rely on powerful LLMs carefully designed specific principles to describe human intentions and are easily influenced by position bias. To address these issues we propose a self-reference-based AI feedback framework that enables a 13B Llama2-Chat to provide high-quality feedback under simple and general principles such as best for humanity. Specifically we allow the AI to first respond to the users instructions then generate criticism of other answers based on its own response as a reference and finally determine which answer better fits human preferences according to the criticism. Additionally we use a self-consistency method to further reduce the impact of position bias and employ semantic perplexity to calculate the preference strength differences between different answers. Experimental results show that our method enables 13B and 70B Llama2-Chat annotators to provide high-quality preference feedback and the policy models trained based on these preference data achieve significant advantages in benchmark datasets through reinforcement learning.
