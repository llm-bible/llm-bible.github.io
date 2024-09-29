---
layout: publication
title: Pattern-Aware Chain-of-Thought Prompting in Large Language Models
authors: Zhang Yufeng, Wang Xuepeng, Wu Lingxiang, Wang Jinqiao
conference: "Arxiv"
year: 2024
bibkey: zhang2024pattern
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14812"}
tags: ['Ethics And Bias', 'Prompting', 'Reinforcement Learning', 'Security']
---
Chain-of-thought (CoT) prompting can guide language models to engage in complex multi-step reasoning. The quality of provided demonstrations significantly impacts the success of downstream inference tasks. While existing automated methods prioritize accuracy and semantics in these demonstrations we show that the underlying reasoning patterns play a more crucial role in such tasks. In this paper we propose Pattern-Aware CoT a prompting method that considers the diversity of demonstration patterns. By incorporating patterns such as step length and reasoning process within intermediate steps PA-CoT effectively mitigates the issue of bias induced by demonstrations and enables better generalization to diverse scenarios. We conduct experiments on nine reasoning benchmark tasks using two open-source LLMs. The results show that our method substantially enhances reasoning performance and exhibits robustness to errors. The code will be made publicly available.
