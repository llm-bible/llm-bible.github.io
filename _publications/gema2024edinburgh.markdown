---
layout: publication
title: Edinburgh Clinical NLP At MEDIQA45;CORR 2024 Guiding Large Language Models With Hints
authors: Gema Aryo Pradipta, Lee Chaeeun, Minervini Pasquale, Daines Luke, Simpson T. Ian, Alex Beatrice
conference: "Arxiv"
year: 2024
bibkey: gema2024edinburgh
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18028"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
The MEDIQA45;CORR 2024 shared task aims to assess the ability of Large Language Models (LLMs) to identify and correct medical errors in clinical notes. In this study we evaluate the capability of general LLMs specifically GPT45;3.5 and GPT45;4 to identify and correct medical errors with multiple prompting strategies. Recognising the limitation of LLMs in generating accurate corrections only via prompting strategies we propose incorporating error45;span predictions from a smaller fine45;tuned model in two ways 1) by presenting it as a hint in the prompt and 2) by framing it as multiple45;choice questions from which the LLM can choose the best correction. We found that our proposed prompting strategies significantly improve the LLMs ability to generate corrections. Our best45;performing solution with 845;shot + CoT + hints ranked sixth in the shared task leaderboard. Additionally our comprehensive analyses show the impact of the location of the error sentence the prompted role and the position of the multiple45;choice option on the accuracy of the LLM. This prompts further questions about the readiness of LLM to be implemented in real45;world clinical settings.
