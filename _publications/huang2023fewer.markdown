---
layout: publication
title: Fewer Is More Boosting LLM Reasoning With Reinforced Context Pruning
authors: Huang Xijie, Zhang Li Lyna, Cheng Kwang-ting, Yang Fan, Yang Mao
conference: "Arxiv"
year: 2023
bibkey: huang2023fewer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.08901"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Pruning', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown impressive capabilities yet they still struggle with math reasoning. In this work we propose CoT45;Influx a novel approach that pushes the boundary of few45;shot Chain45;of45;Thoughts (CoT) learning to improve LLM mathematical reasoning. Motivated by the observation that adding more concise CoT examples in the prompt can improve LLM reasoning performance CoT45;Influx employs a coarse45;to45;fine pruner to maximize the input of effective and concise CoT examples. The pruner first selects as many crucial CoT examples as possible and then prunes unimportant tokens to fit the context window. A math reasoning dataset with diverse difficulty levels and reasoning steps is used to train the pruner along with a math45;specialized reinforcement learning approach. As a result by enabling more CoT examples with double the context window size in tokens CoT45;Influx significantly outperforms various prompting baselines across various LLMs (LLaMA245;7B 13B 70B) and 5 math datasets achieving up to 4.5537; absolute improvements. Remarkably without any fine45;tuning LLaMA245;70B with CoT45;Influx surpasses GPT45;3.5 and a wide range of larger LLMs (PaLM Minerva 540B etc.) on the GSM8K. CoT45;Influx serves as a plug45;and45;play module for LLMs and is compatible with most existing reasoning prompting techniques such as self45;consistency and self45;verification.
