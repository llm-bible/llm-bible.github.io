---
layout: publication
title: Llama Rider Spurring Large Language Models To Explore The Open World
authors: Feng Yicheng, Wang Yuxuan, Liu Jiazheng, Zheng Sipeng, Lu Zongqing
conference: "Arxiv"
year: 2023
bibkey: feng2023llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08922"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recently various studies have leveraged Large Language Models (LLMs) to help decision45;making and planning in environments and try to align the LLMs knowledge with the world conditions. Nonetheless the capacity of LLMs to continuously acquire environmental knowledge and adapt in an open world remains uncertain. In this paper we propose an approach to spur LLMs to explore the open world gather experiences and learn to improve their task45;solving capabilities. In this approach a multi45;round feedback45;revision mechanism is utilized to encourage LLMs to actively select appropriate revision actions guided by feedback information from the environment. This facilitates exploration and enhances the models performance. Besides we integrate sub45;task relabeling to assist LLMs in maintaining consistency in sub45;task planning and help the model learn the combinatorial nature between tasks enabling it to complete a wider range of tasks through training based on the acquired exploration experiences. By evaluation in Minecraft an open45;ended sandbox world we demonstrate that our approach LLaMA45;Rider enhances the efficiency of the LLM in exploring the environment and effectively improves the LLMs ability to accomplish more tasks through fine45;tuning with merely 1.3k instances of collected data showing minimal training costs compared to the baseline using reinforcement learning.
