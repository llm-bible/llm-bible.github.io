---
layout: publication
title: Think45;in45;memory Recalling And Post45;thinking Enable Llms With Long45;term Memory
authors: Liu Lei, Yang Xiaoyan, Shen Yue, Hu Binbin, Zhang Zhiqiang, Gu Jinjie, Zhang Guannan
conference: "Arxiv"
year: 2023
bibkey: liu2023think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08719"}
tags: ['Agentic', 'Ethics And Bias', 'Reinforcement Learning', 'Tools']
---
Memory45;augmented Large Language Models (LLMs) have demonstrated remarkable performance in long45;term human45;machine interactions which basically relies on iterative recalling and reasoning of history to generate high45;quality responses. However such repeated recall45;reason steps easily produce biased thoughts textit123;i.e.125; inconsistent reasoning results when recalling the same history for different questions. On the contrary humans can keep thoughts in the memory and recall them without repeated reasoning. Motivated by this human capability we propose a novel memory mechanism called TiM (Think45;in45;Memory) that enables LLMs to maintain an evolved memory for storing historical thoughts along the conversation stream. The TiM framework consists of two crucial stages (1) before generating a response a LLM agent recalls relevant thoughts from memory and (2) after generating a response the LLM agent post45;thinks and incorporates both historical and new thoughts to update the memory. Thus TiM can eliminate the issue of repeated reasoning by saving the post45;thinking thoughts as the history. Besides we formulate the basic principles to organize the thoughts in memory based on the well45;established operations (textit123;i.e.125; insert forget and merge operations) allowing for dynamic updates and evolution of the thoughts. Furthermore we introduce Locality45;Sensitive Hashing into TiM to achieve efficient retrieval for the long45;term conversations. We conduct qualitative and quantitative experiments on real45;world and simulated dialogues covering a wide range of topics demonstrating that equipping existing LLMs with TiM significantly enhances their performance in generating responses for long45;term interactions.
