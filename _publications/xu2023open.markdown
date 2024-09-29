---
layout: publication
title: Baize An Open45;source Chat Model With Parameter45;efficient Tuning On Self45;chat Data
authors: Xu Canwen, Guo Daya, Duan Nan, Mcauley Julian
conference: "Arxiv"
year: 2023
bibkey: xu2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01196"}
  - {name: "Code", url: "https://github.com/project&#45;baize/baize&#45;chatbot"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Tools']
---
Chat models such as ChatGPT have shown impressive capabilities and have been rapidly adopted across numerous domains. However these models are only accessible through a restricted API creating barriers for new research and progress in the field. We propose a pipeline that can automatically generate a high45;quality multi45;turn chat corpus by leveraging ChatGPT to engage in a conversation with itself. Subsequently we employ parameter45;efficient tuning to enhance LLaMA an open45;source large language model. The resulting model named Baize demonstrates good performance in multi45;turn dialogues with guardrails that minimize potential risks. Furthermore we propose a new technique called Self45;Distill with Feedback to further improve the performance of the Baize models with feedback from ChatGPT. The Baize models and data are released for research purposes only at https://github.com/project&#45;baize/baize&#45;chatbot. An online demo is also available at https://huggingface.co/spaces/project&#45;baize/chat&#45;with&#45;baize.
