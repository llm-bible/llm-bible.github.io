---
layout: publication
title: 'Automated Black-box Prompt Engineering For Personalized Text-to-image Generation'
authors: Yutong He, Alexander Robey, Naoki Murata, Yiding Jiang, Joshua Nathaniel Williams, George J. Pappas, Hamed Hassani, Yuki Mitsufuji, Ruslan Salakhutdinov, J. Zico Kolter
conference: "Arxiv"
year: 2024
bibkey: he2024automated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.19103'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting', 'Merging']
---
Prompt engineering is an effective but labor-intensive way to control
text-to-image (T2I) generative models. Its time-intensive nature and complexity
have spurred the development of algorithms for automated prompt generation.
However, these methods often struggle with transferability across T2I models,
require white-box access to the underlying model, or produce non-intuitive
prompts. In this work, we introduce PRISM, an algorithm that automatically
produces human-interpretable and transferable prompts that can effectively
generate desired concepts given only black-box access to T2I models. Inspired
by large language model (LLM) jailbreaking, PRISM leverages the in-context
learning ability of LLMs to iteratively refine the candidate prompt
distribution built upon the reference images. Our experiments demonstrate the
versatility and effectiveness of PRISM in generating accurate prompts for
objects, styles, and images across multiple T2I models, including Stable
Diffusion, DALL-E, and Midjourney.
