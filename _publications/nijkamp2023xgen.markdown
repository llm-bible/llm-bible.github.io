---
layout: publication
title: Xgen-7b Technical Report
authors: Nijkamp Erik, Xie Tian, Hayashi Hiroaki, Pang Bo, Xia Congying, Xing Chen, Vig Jesse, Yavuz Semih, Laban Philippe, Krause Ben, Purushwalkam Senthil, Niu Tong, Kryściński Wojciech, Murakhovs'ka Lidiya, Choubey Prafulla Kumar, Fabbri Alex, Liu Ye, Meng Rui, Tu Lifu, Bhat Meghana, Wu Chien-sheng, Savarese Silvio, Zhou Yingbo, Joty Shafiq, Xiong Caiming
conference: "Arxiv"
year: 2023
bibkey: nijkamp2023xgen
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03450"}
tags: ['Applications', 'Pretraining Methods', 'Reinforcement Learning']
---
Large Language Models (LLMs) have become ubiquitous across various domains transforming the way we interact with information and conduct research. However most high-performing LLMs remain confined behind proprietary walls hindering scientific progress. Most open-source LLMs on the other hand are limited in their ability to support longer sequence lengths which is a key requirement for many tasks that require inference over an input context. To address this we have trained XGen a series of 7B parameter models on up to 8K sequence length for up to 1.5T tokens. We have also finetuned the XGen models on public-domain instructional data creating their instruction-tuned counterparts (XGen-Inst). We open-source our models for both research advancements and commercial applications. Our evaluation on standard benchmarks shows that XGen models achieve comparable or better results when compared with state-of-the-art open-source LLMs. Our targeted evaluation on long sequence modeling tasks shows the benefits of our 8K-sequence models over 2K-sequence open-source LLMs.
