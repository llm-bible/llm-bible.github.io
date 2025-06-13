---
layout: publication
title: 'Deep Reasoning Translation Via Reinforcement Learning'
authors: Jiaan Wang, Fandong Meng, Jie Zhou
conference: "Arxiv"
year: 2025
bibkey: wang2025deep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10187"}
tags: ['Agentic', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
Recently, deep reasoning LLMs (e.g., OpenAI o1/o3 and DeepSeek-R1) have shown
promising performance in various complex tasks. Free translation is an
important and interesting task in the multilingual world, which requires going
beyond word-for-word translation and taking cultural differences into account.
This task is still under-explored in deep reasoning LLMs. In this paper, we
introduce DeepTrans, a deep reasoning translation model that learns free
translation via reinforcement learning. Specifically, we carefully build a
reward model with pre-defined scoring criteria on both the translation results
and the thought process. Given the source sentences, the reward model teaches
the deep translation model how to think and free-translate them during
reinforcement learning. In this way, training DeepTrans does not need any
labeled translations, avoiding the human-intensive annotation or
resource-intensive data synthesis. Experimental results show the effectiveness
of DeepTrans. Using Qwen2.5-7B as the backbone, DeepTrans improves performance
by 16.3% in literature translation, and outperforms strong deep reasoning
baselines as well as baselines that are fine-tuned with synthesized data.
Moreover, we summarize the failures and interesting findings during our RL
exploration. We hope this work could inspire other researchers in free
translation.
