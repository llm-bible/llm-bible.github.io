---
layout: publication
title: 'Into The Unknown: Self-learning Large Language Models'
authors: Ferdinan Teddy, Kocoń Jan, Kazienko Przemysław
conference: "Arxiv"
year: 2024
bibkey: ferdinan2024into
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09147"}
tags: ['Tools', 'Training Techniques', 'Uncategorized']
---
We address the main problem of self-learning LLM: the question of what to learn. We propose a self-learning LLM framework that enables an LLM to independently learn previously unknown knowledge through self-assessment of their own hallucinations. We introduce a concept called Point in the Unknown (PiU) to identify atomic knowledge unknown to a model, along with four methods for automatic PiUs identification, facilitating the creation of a self-learning loop that focuses exclusively on the absorption of currently unknown knowledge into the model. Additionally, we developed evaluation metrics to gauge an LLM's self-learning capability. Our experiments revealed that LLMs with at least 3B parameters that have undergone some instruction training would be able to perform self-learning well. We further proved the effectiveness of self-learning by comparing the performance of a model that has undergone self-learning to a model that has not. Our self-learning concept allows more efficient LLM updates and opens new perspectives for LLM knowledge exchange.
