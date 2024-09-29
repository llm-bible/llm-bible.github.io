---
layout: publication
title: Mathcoder Seamless Code Integration In Llms For Enhanced Mathematical Reasoning
authors: Wang Ke, Ren Houxing, Zhou Aojun, Lu Zimu, Luo Sichun, Shi Weikang, Zhang Renrui, Song Linqi, Zhan Mingjie, Li Hongsheng
conference: "Arxiv"
year: 2023
bibkey: wang2023seamless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03731"}
  - {name: "Code", url: "https://github.com/mathllm/MathCoder"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
The recently released GPT45;4 Code Interpreter has demonstrated remarkable proficiency in solving challenging math problems primarily attributed to its ability to seamlessly reason with natural language generate code execute code and continue reasoning based on the execution output. In this paper we present a method to fine45;tune open45;source language models enabling them to use code for modeling and deriving math equations and consequently enhancing their mathematical reasoning abilities. We propose a method of generating novel and high45;quality datasets with math problems and their code45;based solutions referred to as MathCodeInstruct. Each solution interleaves natural language code and execution results. We also introduce a customized supervised fine45;tuning and inference approach. This approach yields the MathCoder models a family of models capable of generating code45;based solutions for solving challenging math problems. Impressively the MathCoder models achieve state45;of45;the45;art scores among open45;source LLMs on the MATH (45.237;) and GSM8K (83.937;) datasets substantially outperforming other open45;source alternatives. Notably the MathCoder model not only surpasses ChatGPT45;3.5 and PaLM45;2 on GSM8K and MATH but also outperforms GPT45;4 on the competition45;level MATH dataset. The dataset and models will be released at https://github.com/mathllm/MathCoder.
