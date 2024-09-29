---
layout: publication
title: Promptagent Strategic Planning With Language Models Enables Expert45;level Prompt Optimization
authors: Wang Xinyuan, Li Chenxi, Wang Zhen, Bai Fan, Luo Haotian, Zhang Jiayou, Jojic Nebojsa, Xing Eric P., Hu Zhiting
conference: "Arxiv"
year: 2023
bibkey: wang2023strategic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16427"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Highly effective task45;specific prompts are often heavily engineered by experts to integrate detailed instructions and domain insights based on a deep understanding of both instincts of large language models (LLMs) and the intricacies of the target task. However automating the generation of such expert45;level prompts remains elusive. Existing prompt optimization methods tend to overlook the depth of domain knowledge and struggle to efficiently explore the vast space of expert45;level prompts. Addressing this we present PromptAgent an optimization method that autonomously crafts prompts equivalent in quality to those handcrafted by experts. At its core PromptAgent views prompt optimization as a strategic planning problem and employs a principled planning algorithm rooted in Monte Carlo tree search to strategically navigate the expert45;level prompt space. Inspired by human45;like trial45;and45;error exploration PromptAgent induces precise expert45;level insights and in45;depth instructions by reflecting on model errors and generating constructive error feedback. Such a novel framework allows the agent to iteratively examine intermediate prompts (states) refine them based on error feedbacks (actions) simulate future rewards and search for high45;reward paths leading to expert prompts. We apply PromptAgent to 12 tasks spanning three practical domains BIG45;Bench Hard (BBH) as well as domain45;specific and general NLP tasks showing it significantly outperforms strong Chain45;of45;Thought and recent prompt optimization baselines. Extensive analyses emphasize its capability to craft expert45;level detailed and domain45;insightful prompts with great efficiency and generalizability.
