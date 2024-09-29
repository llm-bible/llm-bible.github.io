---
layout: publication
title: "Tell Your Model Where To Attend: Post-hoc Attention Steering For Llms"
authors: Zhang Qingru, Singh Chandan, Liu Liyuan, Liu Xiaodong, Yu Bin, Gao Jianfeng, Zhao Tuo
conference: "Arxiv"
year: 2023
bibkey: zhang2023tell
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02262"}
  - {name: "Code", url: "https://github.com/QingruZhang/PASTA"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
In human-written articles we often leverage the subtleties of text style such as bold and italics to guide the attention of readers. These textual emphases are vital for the readers to grasp the conveyed information. When interacting with large language models (LLMs) we have a similar need - steering the model to pay closer attention to user-specified information e.g. an instruction. Existing methods however are constrained to process plain text and do not support such a mechanism. This motivates us to introduce PASTA - Post-hoc Attention STeering Approach a method that allows LLMs to read text with user-specified emphasis marks. To this end PASTA identifies a small subset of attention heads and applies precise attention reweighting on them directing the model attention to user-specified parts. Like prompting PASTA is applied at inference time and does not require changing any model parameters. Experiments demonstrate that PASTA can substantially enhance an LLMs ability to follow user instructions or integrate new knowledge from user inputs leading to a significant performance improvement on a variety of tasks e.g. an average accuracy improvement of 2237; for LLAMA-7B. Our code is publicly available at https://github.com/QingruZhang/PASTA .
