---
layout: publication
title: 'Large Language Models As Code Executors: An Exploratory Study'
authors: Chenyang Lyu, Lecheng Yan, Rui Xing, Wenxi Li, Younes Samih, Tianbo Ji, Longyue Wang
conference: "Arxiv"
year: 2024
bibkey: lyu2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06667"}
tags: ['Model Architecture', 'RAG', 'GPT', 'Fine-Tuning', 'Prompting']
---
The capabilities of Large Language Models (LLMs) have significantly evolved,
extending from natural language processing to complex tasks like code
understanding and generation. We expand the scope of LLMs' capabilities to a
broader context, using LLMs to execute code snippets to obtain the output. This
paper pioneers the exploration of LLMs as code executors, where code snippets
are directly fed to the models for execution, and outputs are returned. We are
the first to comprehensively examine this feasibility across various LLMs,
including OpenAI's o1, GPT-4o, GPT-3.5, DeepSeek, and Qwen-Coder. Notably, the
o1 model achieved over 90% accuracy in code execution, while others
demonstrated lower accuracy levels. Furthermore, we introduce an Iterative
Instruction Prompting (IIP) technique that processes code snippets line by
line, enhancing the accuracy of weaker models by an average of 7.22% (with the
highest improvement of 18.96%) and an absolute average improvement of 3.86%
against CoT prompting (with the highest improvement of 19.46%). Our study not
only highlights the transformative potential of LLMs in coding but also lays
the groundwork for future advancements in automated programming and the
completion of complex tasks.
