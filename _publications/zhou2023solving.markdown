---
layout: publication
title: Solving Challenging Math Word Problems Using GPT-4 Code Interpreter with Code-based Self-Verification
authors: Zhou Aojun, Wang Ke, Lu Zimu, Shi Weikang, Luo Sichun, Qin Zipeng, Lu Shaoqing, Jia Anya, Song Linqi, Zhan Mingjie, Li Hongsheng
conference: "Arxiv"
year: 2023
bibkey: zhou2023solving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07921"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG']
---
Recent progress in large language models (LLMs) like GPT-4 and PaLM-2 has brought significant advancements in addressing math reasoning problems. In particular OpenAIs latest version of GPT-4 known as GPT-4 Code Interpreter shows remarkable performance on challenging math datasets. In this paper we explore the effect of code on enhancing LLMs reasoning capability by introducing different constraints on the of GPT-4 Code Interpreter. We found that its success can be largely attributed to its powerful skills in generating and executing code evaluating the output of code execution and rectifying its solution when receiving unreasonable outputs. Based on this insight we propose a novel and effective prompting method explicit ode-based elf-erification~(CSV) to further boost the mathematical reasoning potential of GPT-4 Code Interpreter. This method employs a zero-shot prompt on GPT-4 Code Interpreter to encourage it to use code to self-verify its answers. In instances where the verification state registers as False the model shall automatically amend its solution analogous to our approach of rectifying errors during a mathematics examination. Furthermore we recognize that the states of the verification result indicate the confidence of a solution which can improve the effectiveness of majority voting. With GPT-4 Code Interpreter and CSV we achieve an impressive zero-shot accuracy on MATH dataset (53.9 84.3).
