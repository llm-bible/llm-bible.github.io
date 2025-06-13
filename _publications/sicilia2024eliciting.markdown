---
layout: publication
title: 'Eliciting Uncertainty In Chain-of-thought To Mitigate Bias Against Forecasting Harmful User Behaviors'
authors: Anthony Sicilia, Malihe Alikhani
conference: "Arxiv"
year: 2024
bibkey: sicilia2024eliciting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14744"}
tags: ['Ethics and Bias', 'Training Techniques']
---
Conversation forecasting tasks a model with predicting the outcome of an
unfolding conversation. For instance, it can be applied in social media
moderation to predict harmful user behaviors before they occur, allowing for
preventative interventions. While large language models (LLMs) have recently
been proposed as an effective tool for conversation forecasting, it's unclear
what biases they may have, especially against forecasting the (potentially
harmful) outcomes we request them to predict during moderation. This paper
explores to what extent model uncertainty can be used as a tool to mitigate
potential biases. Specifically, we ask three primary research questions: 1) how
does LLM forecasting accuracy change when we ask models to represent their
uncertainty; 2) how does LLM bias change when we ask models to represent their
uncertainty; 3) how can we use uncertainty representations to reduce or
completely mitigate biases without many training data points. We address these
questions for 5 open-source language models tested on 2 datasets designed to
evaluate conversation forecasting for social media moderation.
