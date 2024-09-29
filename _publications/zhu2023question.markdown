---
layout: publication
title: Question Answering As Programming For Solving Time45;sensitive Questions
authors: Zhu Xinyu, Yang Cheng, Chen Bei, Li Siheng, Lou Jian-guang, Yang Yujiu
conference: "Arxiv"
year: 2023
bibkey: zhu2023question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14221"}
  - {name: "Code", url: "https://github.com/TianHongZXY/qaap"}
tags: ['Applications', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools']
---
Question answering plays a pivotal role in human daily life because it involves our acquisition of knowledge about the world. However due to the dynamic and ever45;changing nature of real45;world facts the answer can be completely different when the time constraint in the question changes. Recently Large Language Models (LLMs) have shown remarkable intelligence in question answering while our experiments reveal that the aforementioned problems still pose a significant challenge to existing LLMs. This can be attributed to the LLMs inability to perform rigorous reasoning based on surface45;level text semantics. To overcome this limitation rather than requiring LLMs to directly answer the question we propose a novel approach where we reframe the textbf123;Q125;uestion textbf123;A125;nswering task textbf123;a125;s textbf123;P125;rogramming (textbf123;QAaP125;). Concretely by leveraging modern LLMs superior capability in understanding both natural language and programming language we endeavor to harness LLMs to represent diversely expressed text as well45;structured code and select the best matching answer from multiple candidates through programming. We evaluate our QAaP framework on several time45;sensitive question answering datasets and achieve decent improvement up to 14.537; over strong baselines. Our codes and data are available at https://github.com/TianHongZXY/qaap
