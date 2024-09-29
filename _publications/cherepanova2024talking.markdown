---
layout: publication
title: Talking Nonsense\: Probing Large Language Models' Understanding Of Adversarial Gibberish Inputs
authors: Cherepanova Valeriia, Zou James
conference: "Arxiv"
year: 2024
bibkey: cherepanova2024talking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17120"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security']
---
Large language models (LLMs) exhibit excellent ability to understand human languages but do they also understand their own language that appears gibberish to us In this work we delve into this question aiming to uncover the mechanisms underlying such behavior in LLMs. We employ the Greedy Coordinate Gradient optimizer to craft prompts that compel LLMs to generate coherent responses from seemingly nonsensical inputs. We call these inputs LM Babel and this work systematically studies the behavior of LLMs manipulated by these prompts. We find that the manipulation efficiency depends on the target texts length and perplexity with the Babel prompts often located in lower loss minima compared to natural prompts. We further examine the structure of the Babel prompts and evaluate their robustness. Notably we find that guiding the model to generate harmful texts is not more difficult than into generating benign texts suggesting lack of alignment for out-of-distribution prompts.
