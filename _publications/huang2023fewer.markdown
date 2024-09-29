---
layout: publication
title: Fewer Is More\: Boosting LLM Reasoning With Reinforced Context Pruning
authors: Huang Xijie, Zhang Li Lyna, Cheng Kwang-ting, Yang Fan, Yang Mao
conference: "Arxiv"
year: 2023
bibkey: huang2023fewer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.08901"}
tags: ['Agentic', 'Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Pruning', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have shown impressive capabilities yet they still struggle with math reasoning. In this work we propose CoT-Influx a novel approach that pushes the boundary of few-shot Chain-of-Thoughts (CoT) learning to improve LLM mathematical reasoning. Motivated by the observation that adding more concise CoT examples in the prompt can improve LLM reasoning performance CoT-Influx employs a coarse-to-fine pruner to maximize the input of effective and concise CoT examples. The pruner first selects as many crucial CoT examples as possible and then prunes unimportant tokens to fit the context window. A math reasoning dataset with diverse difficulty levels and reasoning steps is used to train the pruner along with a math-specialized reinforcement learning approach. As a result by enabling more CoT examples with double the context window size in tokens CoT-Influx significantly outperforms various prompting baselines across various LLMs (LLaMA2-7B 13B 70B) and 5 math datasets achieving up to 4.5537; absolute improvements. Remarkably without any fine-tuning LLaMA2-70B with CoT-Influx surpasses GPT-3.5 and a wide range of larger LLMs (PaLM Minerva 540B etc.) on the GSM8K. CoT-Influx serves as a plug-and-play module for LLMs and is compatible with most existing reasoning prompting techniques such as self-consistency and self-verification.
