---
layout: publication
title: 'Training Dialogue Systems By AI Feedback For Improving Overall Dialogue Impression'
authors: Kai Yoshida, Masahiro Mizukami, Seiya Kawano, Canasai Kruengkrai, Hiroaki Sugiyama, Koichiro Yoshino
conference: "Arxiv"
year: 2025
bibkey: yoshida2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12698"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
To improve user engagement during conversations with dialogue systems, we
must improve individual dialogue responses and dialogue impressions such as
consistency, personality, and empathy throughout the entire dialogue. While
such dialogue systems have been developing rapidly with the help of large
language models (LLMs), reinforcement learning from AI feedback (RLAIF) has
attracted attention to align LLM-based dialogue models for such dialogue
impressions. In RLAIF, a reward model based on another LLM is used to create a
training signal for an LLM-based dialogue model using zero-shot/few-shot
prompting techniques. However, evaluating an entire dialogue only by prompting
LLMs is challenging. In this study, the supervised fine-tuning (SFT) of LLMs
prepared reward models corresponding to 12 metrics related to the impression of
the entire dialogue for evaluating dialogue responses. We tuned our dialogue
models using the reward model signals as feedback to improve the impression of
the system. The results of automatic and human evaluations showed that tuning
the dialogue model using our reward model corresponding to dialogue impression
improved the evaluation of individual metrics and the naturalness of the
dialogue response.
