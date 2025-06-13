---
layout: publication
title: 'Creating Arabic LLM Prompts At Scale'
authors: Abdelrahman El-sheikh, Ahmed Elmogtaba, Kareem Darwish, Muhammad Elmallah, Ashraf Elneima, Hassan Sawaf
conference: "Arxiv"
year: 2024
bibkey: elsheikh2024creating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.05882'}
tags: ['Training Techniques', 'Model Architecture', 'Applications', 'Prompting', 'GPT']
---
The debut of chatGPT and BARD has popularized instruction following text
generation using LLMs, where a user can interrogate an LLM using natural
language requests and obtain natural language answers that matches their
requests. Training LLMs to respond in this manner requires a large number of
worked out examples of user requests (aka prompts) with corresponding gold
responses. In this paper, we introduce two methods for creating such prompts
for Arabic cheaply and quickly. The first methods entails automatically
translating existing prompt datasets from English, such as PromptSource and
Super-NaturalInstructions, and then using machine translation quality
estimation to retain high quality translations only. The second method involves
creating natural language prompts on top of existing Arabic NLP datasets. Using
these two methods we were able to create more than 67.4 million Arabic prompts
that cover a variety of tasks including summarization, headline generation,
grammar checking, open/closed question answering, creative writing, etc. We
show that fine tuning an open 7 billion parameter large language model, namely
base Qwen2 7B, enables it to outperform a state-of-the-art 70 billion parameter
instruction tuned model, namely Llama3 70B, in handling Arabic prompts.
