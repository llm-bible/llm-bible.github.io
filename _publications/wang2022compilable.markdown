---
layout: publication
title: Compilable Neural Code Generation With Compiler Feedback
authors: Wang Xin, Wang Yasheng, Wan Yao, Mi Fei, Li Yitong, Zhou Pingyi, Liu Jin, Wu Hao, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2022
bibkey: wang2022compilable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.05132"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG']
---
Automatically generating compilable programs with (or without) natural language descriptions has always been a touchstone problem for computational linguistics and automated software engineering. Existing deep45;learning approaches model code generation as text generation either constrained by grammar structures in decoder or driven by pre45;trained language models on large45;scale code corpus (e.g. CodeGPT PLBART and CodeT5). However few of them account for compilability of the generated programs. To improve compilability of the generated programs this paper proposes COMPCODER a three45;stage pipeline utilizing compiler feedback for compilable code generation including language model fine45;tuning compilability reinforcement and compilability discrimination. Comprehensive experiments on two code generation tasks demonstrate the effectiveness of our proposed approach improving the success rate of compilation from 44.18 to 89.18 in code completion on average and from 70.3 to 96.2 in text45;to45;code generation respectively when comparing with the state45;of45;the45;art CodeGPT.
