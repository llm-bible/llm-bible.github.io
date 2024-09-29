---
layout: publication
title: Acecoder Utilizing Existing Code To Enhance Code Generation
authors: Li Jia, Zhao Yunfei, Li Yongmin, Li Ge, Jin Zhi
conference: "Arxiv"
year: 2023
bibkey: li2023utilizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.17780"}
tags: ['Applications', 'Prompting', 'Tools']
---
Large Language Models (LLMs) have shown great success in code generation. LLMs take as the input a prompt and output the code. A key question is how to make prompts (i.e. Prompting Techniques). Existing prompting techniques are designed for natural language generation and have low accuracy in code generation. In this paper we propose a new prompting technique named AceCoder. Our motivation is that code generation meets two unique challenges (i.e. requirement understanding and code implementation). AceCoder contains two novel mechanisms (i.e. guided code generation and example retrieval) to solve these challenges. (1) Guided code generation asks LLMs first to analyze requirements and output an intermediate preliminary (e.g. test cases). The preliminary is used to clarify requirements and tell LLMs what to write. (2) Example retrieval selects similar programs as examples in prompts which provide lots of relevant content (e.g. algorithms APIs) and teach LLMs how to write. We apply AceCoder to three LLMs (e.g. Codex) and evaluate it on three public benchmarks using the Pass35;64;k. Results show that AceCoder can significantly improve the performance of LLMs on code generation. (1) In terms of Pass35;64;1 AceCoder outperforms the state45;of45;the45;art baseline by up to 56.437; in MBPP 70.737; in MBJP and 88.437; in MBJSP. (2) AceCoder is effective in LLMs with different sizes (i.e. 6B to 13B) and different languages (i.e. Python Java and JavaScript). (3) Human evaluation shows human developers prefer programs from AceCoder.
