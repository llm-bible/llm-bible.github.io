---
layout: publication
title: 'MULTIVERSE: Exposing Large Language Model Alignment Problems In Diverse Worlds'
authors: Jin Xiaolong, Zhang Zhuo, Zhang Xiangyu
conference: "Arxiv"
year: 2024
bibkey: jin2024exposing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01706"}
tags: ['Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Model (LLM) alignment aims to ensure that LLM outputs match with human values. Researchers have demonstrated the severity of alignment problems with a large spectrum of jailbreak techniques that can induce LLMs to produce malicious content during conversations. Finding the corresponding jailbreaking prompts usually requires substantial human intelligence or computation resources. In this paper, we report that LLMs have different levels of alignment in various contexts. As such, by systematically constructing many contexts, called worlds, leveraging a Domain Specific Language describing possible worlds (e.g., time, location, characters, actions and languages) and the corresponding compiler, we can cost-effectively expose latent alignment issues. Given the low cost of our method, we are able to conduct a large scale study regarding LLM alignment issues in different worlds. Our results show that our method outperforms the-state-of-the-art jailbreaking techniques on both effectiveness and efficiency. In addition, our results indicate that existing LLMs are extremely vulnerable to nesting worlds and programming language worlds. They imply that existing alignment training focuses on the real-world and is lacking in various (virtual) worlds where LLMs can be exploited.
