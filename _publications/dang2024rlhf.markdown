---
layout: publication
title: 'RLHF Can Speak Many Languages: Unlocking Multilingual Preference Optimization For Llms'
authors: John Dang, Arash Ahmadian, Kelly Marchisio, Julia Kreutzer, Ahmet Üstün, Sara Hooker
conference: "Arxiv"
year: 2024
bibkey: dang2024rlhf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02552"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Reinforcement Learning']
---
Preference optimization techniques have become a standard final stage for
training state-of-art large language models (LLMs). However, despite widespread
adoption, the vast majority of work to-date has focused on first-class citizen
languages like English and Chinese. This captures a small fraction of the
languages in the world, but also makes it unclear which aspects of current
state-of-the-art research transfer to a multilingual setting. In this work, we
perform an exhaustive study to achieve a new state-of-the-art in aligning
multilingual LLMs. We introduce a novel, scalable method for generating
high-quality multilingual feedback data to balance data coverage. We establish
the benefits of cross-lingual transfer and increased dataset size in preference
training. Our preference-trained model achieves a 54.4% win-rate against Aya 23
8B, the current state-of-the-art multilingual LLM in its parameter class, and a
69.5% win-rate or higher against widely used models like Gemma-1.1-7B-it,
Llama-3-8B-Instruct, Mistral-7B-Instruct-v0.3. As a result of our study, we
expand the frontier of alignment techniques to 23 languages covering half of
the world's population.
