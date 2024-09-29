---
layout: publication
title: Attention Satisfies A Constraint-Satisfaction Lens on Factual Errors of Language Models
authors: Yuksekgonul Mert, Chandrasekaran Varun, Jones Erik, Gunasekar Suriya, Naik Ranjita, Palangi Hamid, Kamar Ece, Nushi Besmira
conference: "Arxiv"
year: 2023
bibkey: yuksekgonul2023attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15098"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Transformer']
---
We investigate the internal behavior of Transformer-based Large Language Models (LLMs) when they generate factually incorrect text. We propose modeling factual queries as constraint satisfaction problems and use this framework to investigate how the LLM interacts internally with factual constraints. We find a strong positive relationship between the LLMs attention to constraint tokens and the factual accuracy of generations. We curate a suite of 10 datasets containing over 40000 prompts to study the task of predicting factual errors with the Llama-2 family across all scales (7B 13B 70B). We propose SAT Probe a method probing attention patterns that can predict factual errors and fine-grained constraint satisfaction and allow early error identification. The approach and findings take another step towards using the mechanistic understanding of LLMs to enhance their reliability.
