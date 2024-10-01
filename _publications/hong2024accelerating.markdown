---
layout: publication
title: 'Accelerating Multilingual Language Model For Excessively Tokenized Languages'
authors: Hong Jimin, Lee Gibbeum, Cho Jaewoong
conference: "Arxiv"
year: 2024
bibkey: hong2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10660"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent advancements in large language models (LLMs) have remarkably enhanced performances on a variety of tasks in multiple languages. However, tokenizers in LLMs trained primarily on English-centric corpora often overly fragment a text into character or Unicode-level tokens in non-Roman alphabetic languages, leading to inefficient text generation. We introduce a simple yet effective framework to accelerate text generation in such languages. Our approach involves employing a new language model head with a vocabulary set tailored to a specific target language for a pre-trained LLM. This is followed by fine-tuning the new head while incorporating a verification step to ensure the model's performance is preserved. We show that this targeted fine-tuning, while freezing other model parameters, effectively reduces token fragmentation for the target language. Our extensive experiments demonstrate that the proposed framework increases the generation speed by a factor of 1.7 while maintaining the performance of pre-trained multilingual models on target monolingual tasks.
