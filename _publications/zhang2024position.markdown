---
layout: publication
title: Position-Aware Parameter Efficient Fine-Tuning Approach for Reducing Positional Bias in LLMs
authors: Zhang Zheng, Yang Fan, Jiang Ziyan, Chen Zheng, Zhao Zhengyang, Ma Chengyuan, Zhao Liang, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: zhang2024position
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01430"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Recent advances in large language models (LLMs) have enhanced their ability to process long input contexts. This development is particularly crucial for tasks that involve retrieving knowledge from an external datastore which can result in long inputs. However recent studies show a positional bias in LLMs demonstrating varying performance depending on the location of useful information within the input sequence. In this study we conduct extensive experiments to investigate the root causes of positional bias. Our findings indicate that the primary contributor to LLM positional bias stems from the inherent positional preferences of different models. We demonstrate that merely employing prompt-based solutions is inadequate for overcoming the positional preferences. To address this positional bias issue of a pre-trained LLM we developed a Position-Aware Parameter Efficient Fine-Tuning (PAPEFT) approach which is composed of a data augmentation technique and a parameter efficient adapter enhancing a uniform attention distribution across the input context. Our experiments demonstrate that the proposed approach effectively reduces positional bias improving LLMs effectiveness in handling long context sequences for various tasks that require externally retrieved knowledge.
