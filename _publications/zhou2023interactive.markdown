---
layout: publication
title: "Recurrentgpt: Interactive Generation Of (arbitrarily) Long Text"
authors: Zhou Wangchunshu, Jiang Yuchen Eleanor, Cui Peng, Wang Tiannan, Xiao Zhenxin, Hou Yifan, Cotterell Ryan, Sachan Mrinmaya
conference: "Arxiv"
year: 2023
bibkey: zhou2023interactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13304"}
  - {name: "Code", url: "https://github.com/aiwaves-cn/RecurrentGPT"}
  - {name: "Code", url: "https://www.aiwaves.org/recurrentgpt"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
The fixed-size context of Transformer makes GPT models incapable of generating arbitrarily long text. In this paper we introduce RecurrentGPT a language-based simulacrum of the recurrence mechanism in RNNs. RecurrentGPT is built upon a large language model (LLM) such as ChatGPT and uses natural language to simulate the Long Short-Term Memory mechanism in an LSTM. At each timestep RecurrentGPT generates a paragraph of text and updates its language-based long-short term memory stored on the hard drive and the prompt respectively. This recurrence mechanism enables RecurrentGPT to generate texts of arbitrary length without forgetting. Since human users can easily observe and edit the natural language memories RecurrentGPT is interpretable and enables interactive generation of long text. RecurrentGPT is an initial step towards next-generation computer-assisted writing systems beyond local editing suggestions. In addition to producing AI-generated content (AIGC) we also demonstrate the possibility of using RecurrentGPT as an interactive fiction that directly interacts with consumers. We call this usage of generative models by AI As Contents (AIAC) which we believe is the next form of conventional AIGC. We further demonstrate the possibility of using RecurrentGPT to create personalized interactive fiction that directly interacts with readers instead of interacting with writers. More broadly RecurrentGPT demonstrates the utility of borrowing ideas from popular model designs in cognitive science and deep learning for prompting LLMs. Our code is available at https://github.com/aiwaves-cn/RecurrentGPT and an online demo is available at https://www.aiwaves.org/recurrentgpt."
