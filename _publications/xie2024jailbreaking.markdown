---
layout: publication
title: 'Jailbreaking As A Reward Misspecification Problem'
authors: Zhihui Xie, Jiahui Gao, Lei Li, Zhenguo Li, Qi Liu, Lingpeng Kong
conference: "Arxiv"
year: 2024
bibkey: xie2024jailbreaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14393"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Prompting']
---
The widespread adoption of large language models (LLMs) has raised concerns
about their safety and reliability, particularly regarding their vulnerability
to adversarial attacks. In this paper, we propose a novel perspective that
attributes this vulnerability to reward misspecification during the alignment
process. This misspecification occurs when the reward function fails to
accurately capture the intended behavior, leading to misaligned model outputs.
We introduce a metric ReGap to quantify the extent of reward misspecification
and demonstrate its effectiveness and robustness in detecting harmful backdoor
prompts. Building upon these insights, we present ReMiss, a system for
automated red teaming that generates adversarial prompts in a
reward-misspecified space. ReMiss achieves state-of-the-art attack success
rates on the AdvBench benchmark against various target aligned LLMs while
preserving the human readability of the generated prompts. Furthermore, these
attacks on open-source models demonstrate high transferability to closed-source
models like GPT-4o and out-of-distribution tasks from HarmBench. Detailed
analysis highlights the unique advantages of the proposed reward
misspecification objective compared to previous methods, offering new insights
for improving LLM safety and robustness.
