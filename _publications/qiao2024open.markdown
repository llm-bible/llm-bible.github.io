---
layout: publication
title: 'Open-nav: Exploring Zero-shot Vision-and-language Navigation In Continuous Environment With Open-source Llms'
authors: Yanyuan Qiao, Wenqi Lyu, Hui Wang, Zixu Wang, Zerui Li, Yuan Zhang, Mingkui Tan, Qi Wu
conference: "Arxiv"
year: 2024
bibkey: qiao2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18794"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Applications']
---
Vision-and-Language Navigation (VLN) tasks require an agent to follow textual
instructions to navigate through 3D environments. Traditional approaches use
supervised learning methods, relying heavily on domain-specific datasets to
train VLN models. Recent methods try to utilize closed-source large language
models (LLMs) like GPT-4 to solve VLN tasks in zero-shot manners, but face
challenges related to expensive token costs and potential data breaches in
real-world applications. In this work, we introduce Open-Nav, a novel study
that explores open-source LLMs for zero-shot VLN in the continuous environment.
Open-Nav employs a spatial-temporal chain-of-thought (CoT) reasoning approach
to break down tasks into instruction comprehension, progress estimation, and
decision-making. It enhances scene perceptions with fine-grained object and
spatial knowledge to improve LLM's reasoning in navigation. Our extensive
experiments in both simulated and real-world environments demonstrate that
Open-Nav achieves competitive performance compared to using closed-source LLMs.
