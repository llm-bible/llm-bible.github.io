---
layout: publication
title: 'On The Loss Of Context-awareness In General Instruction Fine-tuning'
authors: Yihan Wang, Andrew Bai, Nanyun Peng, Cho-jui Hsieh
conference: "Arxiv"
year: 2024
bibkey: wang2024loss
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02688'}
tags: ['Attention Mechanism', 'Ethics and Bias', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Pre-trained Large Language Models (LLMs) require post-training methods such
as supervised fine-tuning (SFT) on instruction-response pairs to enable
instruction following. However, this process can potentially harm existing
capabilities learned during pre-training. In this paper, we investigate the
loss of context awareness after SFT, where context awareness is defined as the
ability to extract and understand information from user-provided context and
respond accordingly. We identify and demonstrate that the loss of context
awareness, particularly in open-source models, occurs in instruction fine-tuned
LLMs when the chat template is applied to input prompts. We identify that the
performance decline is associated with a bias toward different roles learned
during conversational instruction fine-tuning. We demonstrate this correlation
by visualizing changes in attention allocation after the chat template is
applied and manually steering the attention heads. The bias can be learned from
training examples that align with the model's internal knowledge and rely less
on the user-provided context to generate correct responses. Based on these
observations, we propose a metric to identify context-dependent examples from
general instruction fine-tuning datasets. We then apply conditional instruction
fine-tuning with a context-dependency indicator, enabling the model to preserve
context awareness after SFT. Empirical experiments on four context-dependent
downstream tasks and three pre-trained LLMs of different sizes show that our
method effectively mitigates the loss of context awareness without compromising
general instruction-following capabilities.
