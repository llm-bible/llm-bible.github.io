---
layout: publication
title: 'Xjailbreak: Representation Space Guided Reinforcement Learning For Interpretable LLM Jailbreaking'
authors: Sunbowen Lee, Shiwen Ni, Chi Wei, Shuaimin Li, Liyang Fan, Ahmadreza Argha, Hamid Alinejad-rokny, Ruifeng Xu, Yicheng Gong, Min Yang
conference: "Arxiv"
year: 2025
bibkey: lee2025representation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.16727"}
  - {name: "Code", url: "https://github.com/Aegis1863/xJailbreak"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Has Code', 'Prompting']
---
Safety alignment mechanism are essential for preventing large language models
(LLMs) from generating harmful information or unethical content. However,
cleverly crafted prompts can bypass these safety measures without accessing the
model's internal parameters, a phenomenon known as black-box jailbreak.
Existing heuristic black-box attack methods, such as genetic algorithms, suffer
from limited effectiveness due to their inherent randomness, while recent
reinforcement learning (RL) based methods often lack robust and informative
reward signals. To address these challenges, we propose a novel black-box
jailbreak method leveraging RL, which optimizes prompt generation by analyzing
the embedding proximity between benign and malicious prompts. This approach
ensures that the rewritten prompts closely align with the intent of the
original prompts while enhancing the attack's effectiveness. Furthermore, we
introduce a comprehensive jailbreak evaluation framework incorporating
keywords, intent matching, and answer validation to provide a more rigorous and
holistic assessment of jailbreak success. Experimental results show the
superiority of our approach, achieving state-of-the-art (SOTA) performance on
several prominent open and closed-source LLMs, including Qwen2.5-7B-Instruct,
Llama3.1-8B-Instruct, and GPT-4o-0806. Our method sets a new benchmark in
jailbreak attack effectiveness, highlighting potential vulnerabilities in LLMs.
The codebase for this work is available at
https://github.com/Aegis1863/xJailbreak.
