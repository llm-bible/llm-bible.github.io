---
layout: publication
title: Towards Aligning Language Models With Textual Feedback
authors: Lloret Saüc Abadal, Dhuliawala Shehzaad, Murugesan Keerthiram, Sachan Mrinmaya
conference: "Arxiv"
year: 2024
bibkey: lloret2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16970"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Reinforcement Learning']
---
We present ALT (ALignment with Textual feedback) an approach that aligns language models with user preferences expressed in text. We argue that text offers greater expressiveness enabling users to provide richer feedback than simple comparative preferences and this richer feedback can lead to more efficient and effective alignment. ALT aligns the model by conditioning its generation on the textual feedback. Our method relies solely on language modeling techniques and requires minimal hyper45;parameter tuning though it still presents the main benefits of RL45;based alignment algorithms and can effectively learn from textual feedback. We explore the efficacy and efficiency of textual feedback across different tasks such as toxicity reduction summarization and dialog response generation. We find that ALT outperforms PPO for the task of toxicity reduction while being able to match its performance on summarization with only 2037; of the samples. We also explore how ALT can be used with feedback provided by an existing LLM where we explore an LLM providing constrained and unconstrained textual feedback. We also outline future directions to align models with natural language feedback.
