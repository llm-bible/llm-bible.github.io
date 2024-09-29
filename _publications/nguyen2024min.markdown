---
layout: publication
title: Min P Sampling Balancing Creativity And Coherence At High Temperature
authors: Nguyen Minh, Baker Andrew, Kirsch Andreas, Neo Clement
conference: "Arxiv"
year: 2024
bibkey: nguyen2024min
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01082"}
tags: ['Pretraining Methods', 'Reinforcement Learning']
---
Large Language Models (LLMs) generate longform text by successively sampling the next token based on the probability distribution of the token vocabulary at each decoding step. Current popular truncation sampling methods such as top45;p sampling also known as nucleus sampling often struggle to balance coherence and creativity in generating text particularly when using higher temperatures. To address this issue we propose min45;p a dynamic truncation sampling method that establishes a minimum base percentage threshold for tokens which the scales according to the probability of the top candidate token. Through experiments on several benchmarks such as GPQA GSM8K and AlpacaEval Creative Writing we demonstrate that min45;p improves the coherence and quality of generated text even at high temperatures while also facilitating more creative and diverse outputs compared to top45;p and other sampling methods. As of writing min45;p has been adopted by multiple open45;source LLM implementations and have been independently assessed by members of the open45;source LLM community further validating its practical utility and potential.
