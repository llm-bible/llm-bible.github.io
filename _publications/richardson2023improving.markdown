---
layout: publication
title: SYNDICOM Improving Conversational Commonsense With Error45;injection And Natural Language Feedback
authors: Richardson Christopher, Sundar Anirudh, Heck Larry
conference: "Arxiv"
year: 2023
bibkey: richardson2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10015"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Commonsense reasoning is a critical aspect of human communication. Despite recent advances in conversational AI driven by large language models commonsense reasoning remains a challenging task. In this work we introduce SYNDICOM 45; a method for improving commonsense in dialogue response generation. SYNDICOM consists of two components. The first component is a dataset composed of commonsense dialogues created from a knowledge graph and synthesized into natural language. This dataset includes both valid and invalid responses to dialogue contexts along with natural language feedback (NLF) for the invalid responses. The second contribution is a two45;step procedure training a model to predict natural language feedback (NLF) for invalid responses and then training a response generation model conditioned on the predicted NLF the invalid response and the dialogue. SYNDICOM is scalable and does not require reinforcement learning. Empirical results on three tasks are evaluated using a broad range of metrics. SYNDICOM achieves a relative improvement of 5337; over ChatGPT on ROUGE1 and human evaluators prefer SYNDICOM over ChatGPT 5737; of the time. We will publicly release the code and the full dataset.
