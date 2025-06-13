---
layout: publication
title: 'Controlling Difficulty Of Generated Text For Ai-assisted Language Learning'
authors: Meiqing Jin, Liam Dugan, Chris Callison-burch
conference: "Arxiv"
year: 2025
bibkey: jin2025controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04072"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Practicing conversations with large language models (LLMs) presents a promising alternative to traditional in-person language learning. However, most LLMs generate text at a near-native level of complexity, making them ill-suited for beginner learners (CEFR: A1-A2). In this paper, we investigate whether controllable generation techniques -- specifically modular methods that do not require model fine-tuning -- can adapt LLM outputs to better support absolute beginners. We evaluate these methods through both automatic metrics and a user study with university-level learners of Japanese. Our findings show that while prompting alone fails to control output difficulty, the use of future discriminators (Yang and Klein, 2021) significantly improves output comprehensibility (from 40.4% to 84.3%). We further introduce a novel token-level evaluation metric, Token Miss Rate (TMR), that quantifies the proportion of incomprehensible tokens per utterance and correlates strongly with human judgments. To support future research in AI-assisted language learning, we release our code, models, annotation tools, and dataset.
