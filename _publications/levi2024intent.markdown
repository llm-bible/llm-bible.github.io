---
layout: publication
title: Intent45;based Prompt Calibration Enhancing Prompt Optimization With Synthetic Boundary Cases
authors: Levi Elad, Brosh Eli, Friedmann Matan
conference: "Arxiv"
year: 2024
bibkey: levi2024intent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03099"}
  - {name: "Code", url: "https://github.com/Eladlev/AutoPrompt&#125;&#123;here&#125;"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'Reinforcement Learning']
---
Prompt engineering is a challenging and important task due to the high sensitivity of Large Language Models (LLMs) to the given prompt and the inherent ambiguity of a textual task instruction. Automatic prompt engineering is essential to achieve optimized performance from LLMs. Recent studies have demonstrated the capabilities of LLMs to automatically conduct prompt engineering by employing a meta45;prompt that incorporates the outcomes of the last trials and proposes an improved prompt. However this requires a high45;quality benchmark to compare different prompts which is difficult and expensive to acquire in many real45;world use cases. In this work we introduce a new method for automatic prompt engineering using a calibration process that iteratively refines the prompt to the user intent. During the optimization process the system jointly generates synthetic data of boundary use cases and optimizes the prompt according to the generated dataset. We demonstrate the effectiveness of our method with respect to strong proprietary models on real45;world tasks such as moderation and generation. Our method outperforms state45;of45;the45;art methods with a limited number of annotated samples. Furthermore we validate the advantages of each one of the systems key components. Our system is built in a modular way facilitating easy adaptation to other tasks. The code is available href123;https://github.com/Eladlev/AutoPrompt&#125;&#123;here&#125;$.
