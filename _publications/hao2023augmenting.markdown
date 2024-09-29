---
layout: publication
title: "Toolkengpt: Augmenting Frozen Language Models With Massive Tools Via Tool Embeddings"
authors: Hao Shibo, Liu Tianyang, Wang Zhen, Hu Zhiting
conference: "Arxiv"
year: 2023
bibkey: hao2023augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11554"}
tags: ['Applications', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Augmenting large language models (LLMs) with external tools has emerged as a promising approach to solving complex problems. However traditional methods which finetune LLMs with tool demonstration data can be both costly and restricted to a predefined set of tools. Recent in-context learning paradigm alleviates these issues but the limited context length only allows for a few shots of demonstrations leading to suboptimal understandings of the tools. Moreover when there are numerous tools to choose from in-context learning could completely fail to work. In this paper we propose an alternative approach (textbfToolkenGPT) which combines the benefits of both sides. Our approach represents each (underlinetool) as a to(underlineken) ((textittoolken)) and learns an embedding for it enabling tool calls in the same way as generating a regular word token. Once a toolken is triggered the LLM is prompted to complete arguments for the tool to execute. ToolkenGPT offers the flexibility to plug in an arbitrary number of tools by expanding the set of toolkens on the fly. In addition it improves tool use by allowing extensive demonstration data for learning the toolken embeddings. In diverse domains including numerical reasoning knowledge-based question answering and embodied plan generation our approach effectively augments LLMs with tools and substantially outperforms various latest baselines. ToolkenGPT demonstrates the promising ability to use relevant tools from a large tool set in complex scenarios.
