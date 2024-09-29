---
layout: publication
title: Exploring An LM To Generate Prolog Predicates From Mathematics Questions
authors: Yang Xiaocheng, Tam Yik-cheung
conference: "Arxiv"
year: 2023
bibkey: yang2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03667"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Recently there has been a surge in interest in NLP driven by ChatGPT. ChatGPT a transformer45;based generative language model of substantial scale exhibits versatility in performing various tasks based on natural language. Nevertheless large language models often exhibit poor performance in solving mathematics questions that require reasoning. Prior research has demonstrated the effectiveness of chain45;of45;thought prompting in enhancing reasoning capabilities. Now we aim to investigate whether fine45;tuning a model for the generation of Prolog codes a logic language and subsequently passing these codes to a compiler can further improve accuracy. Consequently we employ chain45;of45;thought to fine45;tune LLaMA7B as a baseline model and develop other fine45;tuned LLaMA7B models for the generation of Prolog code Prolog code + chain45;of45;thought and chain45;of45;thought + Prolog code respectively. The results reveal that the Prolog generation model surpasses the baseline in performance while the combination generation models do not yield significant improvements. The Prolog corpus based on GSM8K and the correspondingly finetuned Prolog generation model based on LLaMA7B are released to the research community.
