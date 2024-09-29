---
layout: publication
title: Occuquest Mitigating Occupational Bias For Inclusive Large Language Models
authors: Xue Mingfeng, Liu Dayiheng, Yang Kexin, Dong Guanting, Lei Wenqiang, Yuan Zheng, Zhou Chang, Zhou Jingren
conference: "Arxiv"
year: 2023
bibkey: xue2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16517"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
The emergence of large language models (LLMs) has revolutionized natural language processing tasks. However existing instruction45;tuning datasets suffer from occupational bias the majority of data relates to only a few occupations which hampers the instruction45;tuned LLMs to generate helpful responses to professional queries from practitioners in specific fields. To mitigate this issue and promote occupation45;inclusive LLMs we create an instruction45;tuning dataset named emph123;OccuQuest125; which contains 110000+ prompt45;completion pairs and 30000+ dialogues covering over 1000 occupations in 26 occupational categories. We systematically request ChatGPT organizing queries hierarchically based on Occupation Responsibility Topic and Question to ensure a comprehensive coverage of occupational specialty inquiries. By comparing with three commonly used datasets (Dolly ShareGPT and WizardLM) we observe that OccuQuest exhibits a more balanced distribution across occupations. Furthermore we assemble three test sets for comprehensive evaluation an occu45;test set covering 25 occupational categories an estate set focusing on real estate and an occu45;quora set containing real45;world questions from Quora. We then fine45;tune LLaMA on OccuQuest to obtain OccuLLaMA which significantly outperforms state45;of45;the45;art LLaMA variants (Vicuna Tulu and WizardLM) on professional questions in GPT45;4 and human evaluations. Notably on the occu45;quora set OccuLLaMA reaches a high win rate of 86.437; against WizardLM.
