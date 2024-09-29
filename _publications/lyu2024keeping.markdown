---
layout: publication
title: Keeping Llms Aligned After Fine-tuning\: The Crucial Role Of Prompt Templates
authors: Lyu Kaifeng, Zhao Haoyu, Gu Xinran, Yu Dingli, Goyal Anirudh, Arora Sanjeev
conference: "Arxiv"
year: 2024
bibkey: lyu2024keeping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18540"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Training Techniques']
---
Public LLMs such as the Llama 2-Chat have driven huge activity in LLM research. These models underwent alignment training and were considered safe. Recently Qi et al. (2023) reported that even benign fine-tuning (e.g. on seemingly safe datasets) can give rise to unsafe behaviors in the models. The current paper is about methods and best practices to mitigate such loss of alignment. Through extensive experiments on several chat models (Metas Llama 2-Chat Mistral AIs Mistral 7B Instruct v0.2 and OpenAIs GPT-3.5 Turbo) this paper uncovers that the prompt templates used during fine-tuning and inference play a crucial role in preserving safety alignment and proposes the Pure Tuning Safe Testing (PTST) principle -- fine-tune models without a safety prompt but include it at test time. Fine-tuning experiments on GSM8K ChatDoctor and OpenOrca show that PTST significantly reduces the rise of unsafe behaviors and even almost eliminates them in some cases.
