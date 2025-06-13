---
layout: publication
title: 'Scribeagent: Towards Specialized Web Agents Using Production-scale Workflow Data'
authors: Junhong Shen, Atishay Jain, Zedian Xiao, Ishan Amlekar, Mouad Hadji, Aaron Podolny, Ameet Talwalkar
conference: "Arxiv"
year: 2024
bibkey: shen2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15004"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large Language Model (LLM) agents are rapidly improving to handle
increasingly complex web-based tasks. Most of these agents rely on
general-purpose, proprietary models like GPT-4 and focus on designing better
prompts to improve their planning abilities. However, general-purpose LLMs are
not specifically trained to understand specialized web contexts such as HTML,
and they often struggle with long-horizon planning. We explore an alternative
approach that fine-tunes open-source LLMs using production-scale workflow data
collected from over 250 domains corresponding to 6 billion tokens. This simple
yet effective approach shows substantial gains over prompting-based agents on
existing benchmarks -- ScribeAgent achieves state-of-the-art direct generation
performance on Mind2Web and improves the task success rate by 7.3% over the
previous best text-only web agents on WebArena. We further perform detailed
ablation studies on various fine-tuning design choices and provide insights
into LLM selection, training recipes, context window optimization, and effect
of dataset sizes.
