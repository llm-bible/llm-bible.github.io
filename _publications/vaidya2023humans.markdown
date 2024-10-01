---
layout: publication
title: 'Humans And Language Models Diverge When Predicting Repeating Text'
authors: Vaidya Aditya R., Turek Javier, Huth Alexander G.
conference: "Arxiv"
year: 2023
bibkey: vaidya2023humans
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06408"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Language models that are trained on the next-word prediction task have been shown to accurately model human behavior in word prediction and reading speed. In contrast with these findings, we present a scenario in which the performance of humans and LMs diverges. We collected a dataset of human next-word predictions for five stimuli that are formed by repeating spans of text. Human and GPT-2 LM predictions are strongly aligned in the first presentation of a text span, but their performance quickly diverges when memory (or in-context learning) begins to play a role. We traced the cause of this divergence to specific attention heads in a middle layer. Adding a power-law recency bias to these attention heads yielded a model that performs much more similarly to humans. We hope that this scenario will spur future work in bringing LMs closer to human behavior.
