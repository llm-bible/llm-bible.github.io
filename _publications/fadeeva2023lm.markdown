---
layout: publication
title: Lm-polygraph: Uncertainty Estimation For Language Models
authors: Fadeeva Ekaterina, Vashurin Roman, Tsvigun Akim, Vazhentsev Artem, Petrakov Sergey, Fedyanin Kirill, Vasilev Daniil, Goncharova Elizaveta, Panchenko Alexander, Panov Maxim, Baldwin Timothy, Shelmanov Artem
conference: "Arxiv"
year: 2023
bibkey: fadeeva2023lm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07383"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Recent advancements in the capabilities of large language models (LLMs) have paved the way for a myriad of groundbreaking applications in various fields. However a significant challenge arises as these models often hallucinate i.e. fabricate facts without providing users an apparent means to discern the veracity of their statements. Uncertainty estimation (UE) methods are one path to safer more responsible and more effective use of LLMs. However to date research on UE methods for LLMs has been focused primarily on theoretical rather than engineering contributions. In this work we tackle this issue by introducing LM-Polygraph a framework with implementations of a battery of state-of-the-art UE methods for LLMs in text generation tasks with unified program interfaces in Python. Additionally it introduces an extendable benchmark for consistent evaluation of UE techniques by researchers and a demo web application that enriches the standard chat dialog with confidence scores empowering end-users to discern unreliable responses. LM-Polygraph is compatible with the most recent LLMs including BLOOMz LLaMA-2 ChatGPT and GPT-4 and is designed to support future releases of similarly-styled LMs.
