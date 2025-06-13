---
layout: publication
title: 'Empo: Emotion Grounding For Empathetic Response Generation Through Preference Optimization'
authors: Ondrej Sotolar, Vojtech Formanek, Alok Debnath, Allison Lahnala, Charles Welch, Lucie Flek
conference: "Arxiv"
year: 2024
bibkey: sotolar2024emotion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19071"}
  - {name: "Code", url: "https://github.com/justtherightsize/empo"}
tags: ['Agentic', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'BERT']
---
Empathetic response generation is a desirable aspect of conversational
agents, crucial for facilitating engaging and emotionally intelligent
multi-turn conversations between humans and machines. Leveraging large language
models for this task has shown promising results, yet challenges persist in
ensuring both the empathetic quality of the responses and retention of the
generalization performance of the models. We propose a novel approach where we
construct theory-driven preference datasets based on emotion grounding and use
them to align LLMs with preference optimization algorithms to address these
challenges. To evaluate empathetic response generation, we employ the
EmpatheticDialogues dataset, assessing empathy with the diff-Epitome and
BERTscore metrics and with multi-dimensional human evaluation. Additionally, we
measure diversity and emotional valence using feature-based methods. We also
evaluate the impact of training on the generalization performance using the
MMLU benchmark and tasks from the Open LLM Leaderboard. The results show that
LLMs can be aligned for empathetic response generation by preference
optimization while retaining their general performance and that emotion
grounding can guide preference dataset creation. We make all datasets, source
code, and models publicly available. https://github.com/justtherightsize/empo
