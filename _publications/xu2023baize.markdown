---
layout: publication
title: Baize An Open-Source Chat Model with Parameter-Efficient Tuning on Self-Chat Data
authors: Xu Canwen, Guo Daya, Duan Nan, Mcauley Julian
conference: "Arxiv"
year: 2023
bibkey: xu2023baize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01196"}
  - {name: "Code", url: "https://github.com/project-baize/baize-chatbot"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Tools']
---
Chat models such as ChatGPT have shown impressive capabilities and have been rapidly adopted across numerous domains. However these models are only accessible through a restricted API creating barriers for new research and progress in the field. We propose a pipeline that can automatically generate a high-quality multi-turn chat corpus by leveraging ChatGPT to engage in a conversation with itself. Subsequently we employ parameter-efficient tuning to enhance LLaMA an open-source large language model. The resulting model named Baize demonstrates good performance in multi-turn dialogues with guardrails that minimize potential risks. Furthermore we propose a new technique called Self-Distill with Feedback to further improve the performance of the Baize models with feedback from ChatGPT. The Baize models and data are released for research purposes only at https://github.com/project-baize/baize-chatbot. An online demo is also available at https://huggingface.co/spaces/project-baize/chat-with-baize.
