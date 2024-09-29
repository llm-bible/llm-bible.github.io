---
layout: publication
title: An In-depth Look At Geminis Language Abilities
authors: Akter Syeda Nahida, Yu Zichun, Muhamed Aashiq, Ou Tianyue, Bäuerle Alex, Cabrera Ángel Alexander, Dholakia Krish, Xiong Chenyan, Neubig Graham
conference: "Arxiv"
year: 2023
bibkey: akter2023look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11444"}
  - {name: "Code", url: "https://github.com/neulab/gemini-benchmark"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture']
---
The recently released Google Gemini class of models are the first to comprehensively report results that rival the OpenAI GPT series across a wide variety of tasks. In this paper we do an in-depth exploration of Geminis language abilities making two contributions. First we provide a third-party objective comparison of the abilities of the OpenAI GPT and Google Gemini models with reproducible code and fully transparent results. Second we take a closer look at the results identifying areas where one of the two model classes excels. We perform this analysis over 10 datasets testing a variety of language abilities including reasoning answering knowledge-based questions solving math problems translating between languages generating code and acting as instruction-following agents. From this analysis we find that Gemini Pro achieves accuracy that is close but slightly inferior to the corresponding GPT 3.5 Turbo on all tasks that we benchmarked. We further provide explanations for some of this under-performance including failures in mathematical reasoning with many digits sensitivity to multiple-choice answer ordering aggressive content filtering and others. We also identify areas where Gemini demonstrates comparably high performance including generation into non-English languages and handling longer and more complex reasoning chains. Code and data for reproduction can be found at https://github.com/neulab/gemini-benchmark"
