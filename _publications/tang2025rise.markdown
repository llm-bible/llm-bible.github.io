---
layout: publication
title: 'The Rise Of Darkness: Safety-utility Trade-offs In Role-playing Dialogue Agents'
authors: Yihong Tang, Kehai Chen, Xuefeng Bai, Zhengyu Niu, Bo Wang, Jie Liu, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: tang2025rise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20757"}
tags: ['Fine-Tuning', 'Responsible AI', 'Agentic', 'Ethics and Bias']
---
Large Language Models (LLMs) have made remarkable advances in role-playing
dialogue agents, demonstrating their utility in character simulations. However,
it remains challenging for these agents to balance character portrayal utility
with content safety because this essential character simulation often comes
with the risk of generating unsafe content. To address this issue, we first
conduct a systematic exploration of the safety-utility trade-off across
multiple LLMs. Our analysis reveals that risk scenarios created by villain
characters and user queries (referred to as risk coupling) contribute to this
trade-off. Building on this, we propose a novel Adaptive Dynamic
Multi-Preference (ADMP) method, which dynamically adjusts safety-utility
preferences based on the degree of risk coupling and guides the model to
generate responses biased toward utility or safety. We further introduce
Coupling Margin Sampling (CMS) into coupling detection to enhance the model's
ability to handle high-risk scenarios. Experimental results demonstrate that
our approach improves safety metrics while maintaining utility.
