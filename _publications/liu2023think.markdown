---
layout: publication
title: 'Think-in-memory: Recalling And Post-thinking Enable Llms With Long-term Memory'
authors: Liu Lei, Yang Xiaoyan, Shen Yue, Hu Binbin, Zhang Zhiqiang, Gu Jinjie, Zhang Guannan
conference: "Arxiv"
year: 2023
bibkey: liu2023think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08719"}
tags: ['Agentic', 'Ethics And Bias', 'Reinforcement Learning', 'Tools']
---
Memory-augmented Large Language Models (LLMs) have demonstrated remarkable performance in long-term human-machine interactions, which basically relies on iterative recalling and reasoning of history to generate high-quality responses. However, such repeated recall-reason steps easily produce biased thoughts, \textit\{i.e.\}, inconsistent reasoning results when recalling the same history for different questions. On the contrary, humans can keep thoughts in the memory and recall them without repeated reasoning. Motivated by this human capability, we propose a novel memory mechanism called TiM (Think-in-Memory) that enables LLMs to maintain an evolved memory for storing historical thoughts along the conversation stream. The TiM framework consists of two crucial stages: (1) before generating a response, a LLM agent recalls relevant thoughts from memory, and (2) after generating a response, the LLM agent post-thinks and incorporates both historical and new thoughts to update the memory. Thus, TiM can eliminate the issue of repeated reasoning by saving the post-thinking thoughts as the history. Besides, we formulate the basic principles to organize the thoughts in memory based on the well-established operations, (\textit\{i.e.\}, insert, forget, and merge operations), allowing for dynamic updates and evolution of the thoughts. Furthermore, we introduce Locality-Sensitive Hashing into TiM to achieve efficient retrieval for the long-term conversations. We conduct qualitative and quantitative experiments on real-world and simulated dialogues covering a wide range of topics, demonstrating that equipping existing LLMs with TiM significantly enhances their performance in generating responses for long-term interactions.
