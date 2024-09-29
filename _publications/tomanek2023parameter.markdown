---
layout: publication
title: Parameter Efficient Tuning Allows Scalable Personalization Of Llms For Text Entry: A Case Study On Abbreviation Expansion
authors: Tomanek Katrin, Cai Shanqing, Venugopalan Subhashini
conference: "Arxiv"
year: 2023
bibkey: tomanek2023parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14327"}
tags: ['Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Abbreviation expansion is a strategy used to speed up communication by limiting the amount of typing and using a language model to suggest expansions. Here we look at personalizing a Large Language Models (LLM) suggestions based on prior conversations to enhance the relevance of predictions particularly when the user data is small (~1000 samples). Specifically we compare fine-tuning prompt-tuning and retrieval augmented generation of expanded text suggestions for abbreviated inputs. Our case study with a deployed 8B parameter LLM on a real user living with ALS and experiments on movie character personalization indicates that (1) customization may be necessary in some scenarios and prompt-tuning generalizes well to those (2) fine-tuning on in-domain data (with as few as 600 samples) still shows some gains however (3) retrieval augmented few-shot selection also outperforms fine-tuning. (4) Parameter efficient tuning allows for efficient and scalable personalization. For prompt-tuning we also find that initializing the learned soft-prompts to user relevant concept tokens leads to higher accuracy than random initialization.
