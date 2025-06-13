---
layout: publication
title: 'Exploring Next Token Prediction In Theory Of Mind (tom) Tasks: Comparative Experiments With GPT-2 And Llama-2 AI Models'
authors: Pavan Yadav, Nikhil Khandalkar, Krishna Shinde, Lokesh B. Ramegowda, Rajarshi Das
conference: "Arxiv"
year: 2025
bibkey: yadav2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15604"}
tags: ['GPT', 'Prompting', 'Model Architecture', 'Reinforcement Learning']
---
Language models have made significant progress in generating coherent text
and predicting next tokens based on input prompts. This study compares the
next-token prediction performance of two well-known models: OpenAI's GPT-2 and
Meta's Llama-2-7b-chat-hf on Theory of Mind (ToM) tasks. To evaluate their
capabilities, we built a dataset from 10 short stories sourced from the Explore
ToM Dataset. We enhanced these stories by programmatically inserting additional
sentences (infills) using GPT-4, creating variations that introduce different
levels of contextual complexity. This setup enables analysis of how increasing
context affects model performance. We tested both models under four temperature
settings (0.01, 0.5, 1.0, 2.0) and evaluated their ability to predict the next
token across three reasoning levels. Zero-order reasoning involves tracking the
state, either current (ground truth) or past (memory). First-order reasoning
concerns understanding another's mental state (e.g., "Does Anne know the apple
is salted?"). Second-order reasoning adds recursion (e.g., "Does Anne think
that Charles knows the apple is salted?").
  Our results show that adding more infill sentences slightly reduces
prediction accuracy, as added context increases complexity and ambiguity.
Llama-2 consistently outperforms GPT-2 in prediction accuracy, especially at
lower temperatures, demonstrating greater confidence in selecting the most
probable token. As reasoning complexity rises, model responses diverge more.
Notably, GPT-2 and Llama-2 display greater variability in predictions during
first- and second-order reasoning tasks. These findings illustrate how model
architecture, temperature, and contextual complexity influence next-token
prediction, contributing to a better understanding of the strengths and
limitations of current language models.
