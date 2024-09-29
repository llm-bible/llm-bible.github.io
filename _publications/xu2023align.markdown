---
layout: publication
title: Align On The Fly Adapting Chatbot Behavior To Established Norms
authors: Xu Chunpu, Chern Steffi, Chern Ethan, Zhang Ge, Wang Zekun, Liu Ruibo, Li Jing, Fu Jie, Liu Pengfei
conference: "Arxiv"
year: 2023
bibkey: xu2023align
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15907"}
  - {name: "Code", url: "https://github.com/GAIR-NLP/OPO"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
In this paper we aim to align large language models with the ever-changing complex and diverse human values (e.g. social norms) across time and locations. This presents a challenge to existing alignment techniques such as supervised fine-tuning which internalize values within model parameters. To overcome this we propose an On-the-fly Preference Optimization (OPO) method which is a real-time alignment that works in a streaming way. It employs an external memory to store established rules for alignment which can constrain LLMs behaviors without further training allowing for convenient updates and customization of human values. We also introduce a scalable evaluation to assess the proposed method more effectively. Experimental results on both human-annotated and auto-generated questions from legal and moral domains indicate the effectiveness of the proposed OPO method. Our code and data are released at https://github.com/GAIR-NLP/OPO.
