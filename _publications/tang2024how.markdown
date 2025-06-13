---
layout: publication
title: 'How To Build A Pre-trained Multimodal Model For Simultaneously Chatting And Decision-making?'
authors: Zuojin Tang, Bin Hu, Chenyang Zhao, De Ma, Gang Pan, Bin Liu
conference: "Arxiv"
year: 2024
bibkey: tang2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15885"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Existing large pre-trained models typically map text input to text output in
an end-to-end manner, such as ChatGPT, or map a segment of text input to a
hierarchy of action decisions, such as OpenVLA. However, humans can
simultaneously generate text and actions when receiving specific input signals.
For example, a driver can make precise driving decisions while conversing with
a friend in the passenger seat. Motivated by this observation, we consider the
following question in this work: is it possible to construct a pre-trained
model that can provide both language interaction and precise decision-making
capabilities in dynamic open scenarios. We provide a definitive answer to this
question by developing a new model architecture termed Visual Language Action
model for Chatting and Decision Making (VLA4CD), and further demonstrating its
performance in challenging autonomous driving tasks. Specifically, we leverage
LoRA to fine-tune a pre-trained LLM with data of multiple modalities covering
language, visual, and action. Unlike the existing LoRA operations used for LLM
fine-tuning, we have designed new computational modules and training cost
functions for VLA4CD. These designs enable VLA4CD to provide continuous-valued
action decisions while outputting text responses. In contrast, existing LLMs
can only output text responses, and current VLA models can only output action
decisions. Moreover, these VLA models handle action data by discretizing and
then tokenizing the discretized actions, a method unsuitable for complex
decision-making tasks involving high-dimensional continuous-valued action
vectors, such as autonomous driving. The experimental results on CARLA validate
that: (1) our proposed model construction method is effective; (2) compared to
the SOTA VLA model, VLA4CD can provide more accurate real-time decision-making
while retaining the text interaction capability inherent to LLMs.
