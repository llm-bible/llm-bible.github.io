---
layout: publication
title: On The Worst Prompt Performance Of Large Language Models
authors: Cao Bowen, Cai Deng, Zhang Zhisong, Zou Yuexian, Lam Wai
conference: "Arxiv"
year: 2024
bibkey: cao2024worst
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10248"}
  - {name: "Code", url: "https://github.com/cbwbuaa/On&#45;the&#45;Worst&#45;Prompt&#45;"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security']
---
The performance of large language models (LLMs) is acutely sensitive to the phrasing of prompts which raises significant concerns about their reliability in real45;world scenarios. Existing studies often divide prompts into task45;level instructions and case45;level inputs and primarily focus on evaluating and improving robustness against variations in tasks45;level instructions. However this setup fails to fully address the diversity of real45;world user queries and assumes the existence of task45;specific datasets. To address these limitations we introduce RobustAlpacaEval a new benchmark that consists of semantically equivalent case45;level queries and emphasizes the importance of using the worst prompt performance to gauge the lower bound of model performance. Extensive experiments on RobustAlpacaEval with ChatGPT and six open45;source LLMs from the Llama Mistral and Gemma families uncover substantial variability in model performance; for instance a difference of 45.4837; between the worst and best performance for the Llama45;245;70B45;chat model with its worst performance dipping as low as 9.3837;. We further illustrate the difficulty in identifying the worst prompt from both model45;agnostic and model45;dependent perspectives emphasizing the absence of a shortcut to characterize the worst prompt. We also attempt to enhance the worst prompt performance using existing prompt engineering and prompt consistency methods but find that their impact is limited. These findings underscore the need to create more resilient LLMs that can maintain high performance across diverse prompts. Data and code are available at https://github.com/cbwbuaa/On&#45;the&#45;Worst&#45;Prompt&#45; Performance45;of45;LLMs.
