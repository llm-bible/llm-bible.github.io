---
layout: publication
title: Automated Black45;box Prompt Engineering For Personalized Text45;to45;image Generation
authors: He Yutong, Robey Alexander, Murata Naoki, Jiang Yiding, Williams Joshua, Pappas George J., Hassani Hamed, Mitsufuji Yuki, Salakhutdinov Ruslan, Kolter J. Zico
conference: "Arxiv"
year: 2024
bibkey: he2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19103"}
tags: ['Merging', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Prompt engineering is effective for controlling the output of text45;to45;image (T2I) generative models but it is also laborious due to the need for manually crafted prompts. This challenge has spurred the development of algorithms for automated prompt generation. However these methods often struggle with transferability across T2I models require white45;box access to the underlying model and produce non45;intuitive prompts. In this work we introduce PRISM an algorithm that automatically identifies human45;interpretable and transferable prompts that can effectively generate desired concepts given only black45;box access to T2I models. Inspired by large language model (LLM) jailbreaking PRISM leverages the in45;context learning ability of LLMs to iteratively refine the candidate prompts distribution for given reference images. Our experiments demonstrate the versatility and effectiveness of PRISM in generating accurate prompts for objects styles and images across multiple T2I models including Stable Diffusion DALL45;E and Midjourney.
